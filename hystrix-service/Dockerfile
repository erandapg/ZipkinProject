FROM openjdk:8
EXPOSE 8080
ADD ./build/libs/hystrix-service-0.0.1.jar ./hystrix-service-0.0.1.jar
ENTRYPOINT ["java","-jar","-Duser.timezone=GMT+0530","hystrix-service-0.0.1.jar"]	