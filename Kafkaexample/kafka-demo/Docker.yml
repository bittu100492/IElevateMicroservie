#Start with a base image containing Java runtime
FROM openjdk:17-jdk-slim

#Information around who maintains the image
#MAINTAINER eazybytes.com

# Add the application's jar to the image
COPY target/kafka-demo-0.0.1-SNAPSHOT.jar kafka-demo-0.0.1-SNAPSHOT.jar

# execute the application
ENTRYPOINT ["java", "-jar", "kafka-demo-0.0.1-SNAPSHOT.jar"]
