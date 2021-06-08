FROM openjdk:8
EXPOSE 8080
ADD ./build/libs/zuul-service-0.0.1.jar ./zuul-service-0.0.1.jar
ENTRYPOINT ["java","-jar","-Duser.timezone=GMT+0530","zuul-service-0.0.1.jar"]	