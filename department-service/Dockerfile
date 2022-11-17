FROM openjdk:19-oracle

EXPOSE 9001

ADD target/department-service.jar department-service.jar

ENTRYPOINT ["java", "-jar", "department-service.jar"]