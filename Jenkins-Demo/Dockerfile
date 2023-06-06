FROM openjdk:17
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} jenkinsdemo.jar
ENTRYPOINT ["java","-jar","/jenkinsdemo.jar"]
EXPOSE 9001