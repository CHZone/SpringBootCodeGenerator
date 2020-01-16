FROM java:8-jdk-alpine

COPY ./target/generator-web-2.0.jar /usr/app/

WORKDIR /usr/app

RUN sh -c 'touch generator-web-2.0.jar'

ENTRYPOINT ["java", "-jar", "generator-web-2.0.jar"]