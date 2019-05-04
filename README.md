# Micro Services Eureka Server (Discovery Server)
will be responsible for communication across different microservices (clients)
Each microservice will register itself in this server then it will be available for other microservices

# Some parts this service code is copied from my open source eureka-server  
<a href="https://github.com/JavaAdore/eureka-server">https://github.com/JavaAdore/eureka-server</a>

The following environment variables should be presented
# SURVEY_EUREKA_SERVER_PORT=8761
8761 ia default port of survey-eureka-server, but it could be replaced with any unused port

# build
as root/Administration <br/>
mvn clean install docker:removeImage docker:build
# run
java -jar target/survey-survey-eureka-server.jar

# browse
<a href="http://127.0.0.1:8761">http://127.0.0.1:8761</a>



