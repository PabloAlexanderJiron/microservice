FROM maven:3.6.2-jdk-8
ADD /target/zuulserver-0.0.1-SNAPSHOT.jar zuulserver-0.0.1-SNAPSHOT.jar
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "zuulserver-0.0.1-SNAPSHOT.jar"]