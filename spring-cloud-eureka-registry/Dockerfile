#Official JDK11 image
#FROM java:openjdk-11-jdk
FROM java:openjdk-11-alpine
ADD target/SpringCloudEureka-0.0.1-SNAPSHOT.jar /opt/SpringCloudEureka-0.0.1-SNAPSHOT.jar
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "/opt/SpringCloudEureka-0.0.1-SNAPSHOT.jar"]
