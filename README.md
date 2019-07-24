Eureka discovery server must be up and running
Application services should be up and running and they should have registered themselves with the eureka discovery server
Now the Application client would be able to access the application service by using the service identifier and getting hold of the instance.
You can test this Spring Boot App by using:
http://localhost:8080/
Response will be below depending on which instance of service the client is able to connect:
Hello from instance 1 
Hello from instance 2
