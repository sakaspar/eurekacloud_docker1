#Official JDK11 image
#FROM java:openjdk-11-jdk
FROM java:openjdk-11-alpine
ADD target/SpringBootService1-0.0.1-SNAPSHOT.jar /opt/SpringBootService1-0.0.1-SNAPSHOT.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/opt/SpringBootService1-0.0.1-SNAPSHOT.jar"]
