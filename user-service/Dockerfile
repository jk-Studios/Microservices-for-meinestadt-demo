FROM openjdk:19-oracle

EXPOSE 9002

ADD target/user-service.jar user-service.jar

ENTRYPOINT ["java", "-jar", "user-service.jar"]