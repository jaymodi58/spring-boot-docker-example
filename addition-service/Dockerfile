FROM openjdk
 
MAINTAINER Jay Modi

ENTRYPOINT ["/usr/bin/java", "-jar", "/usr/share/addition-service/addition-service-0.0.1-SNAPSHOT.jar"]
 
# Add Maven dependencies
ADD target/addition-service-0.0.1-SNAPSHOT.jar /usr/share/addition-service/addition-service-0.0.1-SNAPSHOT.jar