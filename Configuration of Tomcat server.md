step 1> Install the latest Tomcat server ( Tomcat version 10.1) from the official website: https://tomcat.apache.org/download-10.cgi
step 2> Configuration of Tomcat server 
  port no : [It should be any port at which no existing server exists] [9092 || 8080 ] 
step 3> Setup the username and password 
  username and password: This is the login and password, This is needed to check the overall overview of the Tomcat server 
  with the different role 
      manager-gui - allows access to the HTML GUI and the status pages
      manager-script - allows access to the text interface and the status pages
      manager-jmx - allows access to the JMX proxy and the status pages
      manager-status - allows access to the status pages only
REFER THE IMAGE (setup.jpg) 

step 4> To set the path for your Virtual Machine (JVM)
 In my case, it is: "D:\Downloads\jdk-21_windows-x64_bin\jdk-21.0.1\bin"
and you are done with some basic setup.


NOW TO CHECK WHETHER THE SERVER IS RUNNING OR NOT
http://localhost:<PORT NO>
		->> http://localhost:9092 
