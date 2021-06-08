FROM openjdk:8
EXPOSE 8080
ADD ./build/libs/eureka-service-0.0.1.jar ./eureka-service-0.0.1.jar
ENTRYPOINT ["java","-jar","-Duser.timezone=GMT+0530","eureka-service-0.0.1.jar"]	