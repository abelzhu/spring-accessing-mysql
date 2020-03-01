## spring-accessing-mysql
spring accessing mysql for experience

## Steps:
Prepare mysql: docker:
1. Docker pull mysql
2. docker run --name test-mysql -e MYSQL_ROOT_PASSWORD=123456 -p 3306:3306 -d mysql
3. docker exec -it test-mysql bash

Reference: https://spring.io/guides/gs/accessing-data-mysql/
