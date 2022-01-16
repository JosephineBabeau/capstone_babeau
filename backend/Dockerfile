FROM ubuntu:18.04
COPY backendJavaWebServer /app/backendJavaWebServer
COPY jdk-14.0.2 /app/jdk-14.0.2
CMD app/jdk-14.0.2/bin/java -jar /app/backendJavaWebServer/target/backendJavaWebServer-1.0-SNAPSHOT-jar-with-dependencies.jar
