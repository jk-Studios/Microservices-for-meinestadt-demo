FROM openjdk:19-oracle

EXPOSE 9295 8080 9191

ADD target/hystrix-dashboard.jar hystrix-dashboard.jar

ENTRYPOINT ["java", "-jar", "hystrix-dashboard.jar"]