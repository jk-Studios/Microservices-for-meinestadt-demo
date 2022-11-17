FROM openjdk:19-oracle

EXPOSE 9191

ADD target/cloud-gateway.jar cloud-gateway.jar

ENTRYPOINT ["java", "-jar", "cloud-gateway.jar"]