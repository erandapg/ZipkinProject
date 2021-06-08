FROM openjdk:8
EXPOSE 8080
ADD ./build/libs/zipkin-service-0.0.1.jar ./zipkin-service-0.0.1.jar
ENTRYPOINT ["java","-jar","-Duser.timezone=GMT+0530","zipkin-service-0.0.1.jar"]	