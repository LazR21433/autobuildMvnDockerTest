FROM maven
ADD /src/ /test/src/
ADD /pom.xml /test/pom.xml
WORKDIR /test
RUN mvn clean install
CMD java -jar target/test-0.0.1-SNAPSHOT.jar
#CMD ["/usr/bin/java", "-jar", "/test/target/test-0.0.1-SNAPSHOT.jar"]
#CMD /bin/bash