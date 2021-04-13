FROM maven:3.5.4-jdk-8-alpine as maven

WORKDIR /app
 
# copy the packaged jar file into our docker image
#COPY target/*.jar /trailHello.jar

# set the startup command to execute the jar
CMD ["java", "-jar", "target/*.jar"]