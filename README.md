# Spring Boot 3 project

Project from Alura course

### Important links

Trello: https://trello.com/b/O0lGCsKb/api-voll-med </br>
Prototype: https://www.figma.com/file/N4CgpJqsg7gjbKuDmra3EV/Voll.med

---
## Deploy settings
`mvn package`
```sh
java -Dspring.profiles.active=prod -DDATASOURCE_URL=jdbc:mysql://localhost/vollmed -DDATASOURCE_USERNAME=root -DDATASOURCE_PASSWORD= -jar api-0.0.1-SNAPSHOT.jar
```