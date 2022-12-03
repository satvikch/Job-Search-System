# SER531-Final-Project-Job-Search-System

BackEnd

Pre-Requistes:

  1. Install Java JDK8 on the system.
  2. Set JAVA_HOME environment variable.
  3. PATH variable has JDK path.
  4. Install Maven.

Setup Instructions for local machine.

  If project is cloned/imported on Eclipse IDE:
    You can choose to simply right click on JobsApplication.java, click Run As > Java Application.
  The application will start-up on http://localhost:8080.
  Alternatively,
    You can open Terminal/Command Prompt at the project root folder, run 'mvn clean install'.
  This will create a jar file upon successful build.
  Run 'java -jar target\swe-0.0.1-SNAPSHOT.jar'.
  This should boot up the application.
  To test you can go to http://localhost:8080 on the web browser.

FrontEnd

Pre-Requistes:

Install node.js on the system using 'npm install'
Tested it using 'npm test'
npm installed (usually bundled with node.js installer, so you may not have to do anything here).
Type node -v and npm -v on Command Prompt/Terminal and make sure it displays both versions.
Make sure BackEnd code is downloaded, set up and server is running.

Setup Instructions for local machine.

  Download the code and open index.js file.
  For the variable sparqlService, replace the current URL with the backend service endpoint. Ex: http://localhost:8080.
  Save the file.
  Open Terminal/Command Prompt and run the following commands:
  npm install
  npm test
  You can see the application running at http://localhost:3000 on your web browser.
  
EC2 Instance 
  Created Aws account for our team
  Added three instances 
  Uploaded out turtle files into all the three instances
  Added fuseki server port to all the three instances and installed the server in the instances
  Uploaded the ttl files into the fuseki server using
    ./fuseki-server --update --file = file.ttl /DtabaseName
  The server will start running
  Used the url of instances to fetch data 
   
  
  
