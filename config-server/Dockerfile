FROM openjdk:11
WORKDIR usr/src
COPY ./target/config-server-0.0.1-SNAPSHOT.jar /usr/src/config-server-0.0.1-SNAPSHOT.jar
#  ENV MYSQL_DATABASE=movieDb
#  ENV MYSQL_USER=root_app
#  ENV MYSQL_PASSWORD=root123
#  ENV MYSQL_CI_URL=jdbc:mysql://docker-mysql:3306/movieDb
EXPOSE 8888
ENTRYPOINT ["java","-jar","/usr/src/config-server-0.0.1-SNAPSHOT.jar"]
