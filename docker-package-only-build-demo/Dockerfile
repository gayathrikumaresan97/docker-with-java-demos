# we will use openjdk 8 with alpine as it is a very small linux distro
FROM adoptopenjdk/openjdk8:alpine

# copy the packaged jar file into our docker image
COPY target/demo-0.0.1-SNAPSHOT.jar /demo.jar

# execute the jar
CMD ["java", "-jar", "/demo.jar"]
