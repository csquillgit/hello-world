FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY ./build/libs/HelloBoot-0.0.1-SNAPSHOT.jar /home/HelloBoot-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/home/HelloBoot-0.0.1-SNAPSHOT.jar"]
