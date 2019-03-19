FROM maven:3.5-jdk-8
EXPOSE 8080
VOLUME /tmp
ARG JAR=spring-petclinic-2.1.0.BUILD-SNAPSHOT.jar
COPY target/$JAR /app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
