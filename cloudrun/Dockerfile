FROM openjdk:14-alpine
COPY target/cloudrun-*.jar cloudrun.jar
EXPOSE 8080
CMD ["java", "-Dcom.sun.management.jmxremote", "-Xmx128m", "-jar", "cloudrun.jar"]