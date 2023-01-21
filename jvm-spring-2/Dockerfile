# openjdk11
FROM openjdk:11-jdk
# install curl
RUN apt-get update && apt-get install curl -y
# install telnet
RUN apt install -y telnet
#generate jar
COPY ./target/jvm-spring-2-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]