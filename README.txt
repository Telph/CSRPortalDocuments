TO DEPLOY THE WAR FILE IN YOUR MACHINE:
---------------------------------------
Prerequisite:
 -- I have used Tomcat 8 as my local server. 
 -- Download Tomcat 8 and install it on your machine. (set CATALINA_HOME variable to the bin's parent folder)
 --
1) To execute the WAR file, download it.
2) Place it in the webapps folder of installed tomcat
3) Execute startup.bat available in the bin folder of your installed tomcat
4) The server starts on the configured port in your PC.
5) Once the server starts without any error, you can access this application using the below link.
   http://localhost:portno/CSRPortal/homepage.html
   http://localhost:portno/CSRPortal/aboutus.html
6) Certain REST services will be exposed by the hosted application that can be accessed as
   http://localhost:portno/CSRPortal/rest/*
   * - to be replaced with the actual rest path. Details of this path can be found in the Overview document.
