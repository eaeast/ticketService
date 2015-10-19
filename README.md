# ticketService 


To Test:
mvn clean test
See tests in src/test/java/*.Test

Assumptions
Maven setup and can canload jars from repository (internet)



Import into Eclipse:
mvn eclipse:eclipse -DdownloadSources=true -DdownloadJavadocs=true
In Eclipse, File->Import and select the main folder



Versions of Software used:
Apache Maven 3.1.1 
Java version: 1.7.0_75, vendor: Oracle Corporation






NOTE: Camel stub 
mvn clean camel:run  
It runs,but is just a stub.  TBD extentions.
After mvn camel:run, open a browser and enter:
http://localhost/test?performance=a

See src/main/java/com/east/MyRouteBuilder.java for camel route for "test"
See src/main/resources/META-INF/spring/camel-context.xml for spring context file/config
