FROM adoptopenjdk:11-jre-hotspot
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} demo-crud-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/demo-crud-0.0.1-SNAPSHOT.jar"]