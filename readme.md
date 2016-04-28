# MicroService

### Linkes:
1.weather service: http://localhost:8040/weather?zip=*****

2.book service: http://localhost:8050/book?bibkeys=[ISBN]  (The API supports both ISBN 10 and 13. ex. 0451526538)


#### to run:
* 1. go to each service folder
* 2. mvn install
* 3. mvn spring-boot:run
* 4. need to start eureka serivice so others can run

#### to add a service:
* 1.copy the weatherService folder
* 2.change the names and logic in Controller
* 3.change the port in resources\application.yml for this package
* 4 done!



