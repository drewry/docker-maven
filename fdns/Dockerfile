FROM maven:3.5.3-jdk-8

RUN mkdir -p /usr/src/app
COPY pom.xml /usr/src/app
WORKDIR /usr/src/app
RUN mvn dependency:resolve
