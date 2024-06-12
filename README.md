# Job-Search-System

We implement a structured approach that secures data from multiple job hosting platforms and structures the data with coherency for efficient search queries. The searching algorithms apply constraints on the metadata based on the hyperparameters invoked by the user, such as location, type of job, and title of the job.


**BackEnd**

Pre-Requistes:

  1. Install Java JDK8 on the system.
  2. Set JAVA_HOME environment variable.
  3. PATH variable has JDK path.
  4. Install Maven.

Setup Instructions for local machine.

  1. If project is cloned/imported on Eclipse IDE:
      You can choose to simply right click on JobsApplication.java, click Run As > Java Application.
  2. The application will start-up on http://localhost:8080.
  3. Alternatively,
    You can open Terminal/Command Prompt at the project root folder, run 'mvn clean install'.
    This will create a jar file upon successful build.
    Run 'java -jar target\swe-0.0.1-SNAPSHOT.jar'.
    This should boot up the application.
    To test you can go to http://localhost:8080 on the web browser.

**FrontEnd**

Pre-Requistes:

1. Install node.js on the system using 'npm install'
2. Tested it using 'npm test'
3. npm installed (usually bundled with node.js installer, so you may not have to do anything here).
4. Type node -v and npm -v on Command Prompt/Terminal and make sure it displays both versions.
5. Make sure BackEnd code is downloaded, set up and server is running.

Setup Instructions for local machine.

  1. Download the code and open index.js file.
  2. For the variable sparqlService, replace the current URL with the backend service endpoint. Ex: http://localhost:8080.
  3. Save the file.
  4. Open Terminal/Command Prompt and run the following commands:
  5. npm install
  6. npm test
  7. You can see the application running at http://localhost:3000 on your web browser.
  
**EC2 Instance **
  1. Created Aws account for our team
  2. Added three instances 
  3. Uploaded out turtle files into all the three instances
  4. Added fuseki server port to all the three instances and installed the server in the instances
  5. Uploaded the ttl files into the fuseki server using
    ./fuseki-server --update --file = file.ttl /DtabaseName
  6. The server will start running
  7. Used the url of instances to fetch data 
   
  
  
