FROM openjdk:17-oracle
ARG JAR_FILE=ocp2/*.jar
COPY ${JAR_FILE} ocp-test-1-2.jar
ENTRYPOINT ["java","-jar","/ocp-test-1-2.jar"]
