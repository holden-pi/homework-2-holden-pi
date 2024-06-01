FROM adoptopenjdk/openjdk11:jdk-11.0.10_9-debian
VOLUME /tmp
ARG JAR_FILE
COPY ${JAR_FILE} /app.jar
ENTRYPOINT ["java","-jar","/app.jar"]