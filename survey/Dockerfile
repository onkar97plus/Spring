# FROM tomcat:9.0-jdk15
# COPY survey.war /usr/local/tomcat/webapps/

FROM openjdk:15
RUN ls
RUN pwd
COPY lib/jenkins/workspace/spring pipeline/survey/src/SpringSurvey.jar
# COPY target/spring-boot-docker.jar app.jar
ENTRYPOINT  ["java", "-jar", "app.jar"]
