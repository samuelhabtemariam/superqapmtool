FROM ubuntu:latest

MAINTAINER Samuel Habtemariam "Samuel.habt@gmail.com"

RUN apt-get update && apt-get install -y openjdk-8-jdk

WORKDIR /usr/local/bin/

ADD target/superqapmtool-0.0.1-SNAPSHOT.jar .

CMD ["java", "-jar", "superqapmtool-0.0.1-SNAPSHOT.jar"]
