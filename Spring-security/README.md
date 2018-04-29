# Tag 1.0
# RESTful-service
convert wordladder by java to a RESTful service using spring boot

## 1. run this project using Eclipse
## 2. type URL at browser like:
        http://localhost:8080/wordladder?dictname=smalldict1.txt&word1=bee&word2=bog
## 3. the result will show within interface like:
        A ladder from bog back to bee: bog beg bee

# Tag 2.0 (something wrong with the tag 2.0 please download the most new )
# Add spring-security to origin spring boot starter project

## 1. add this project to Eclipse
## 2. update the dependencies
## 3. run as "Spring Boot App"
#### if run on server like tomcat, some strange bug occurrs: path cannot be find
## 4. type URL like blow try to access wordladder:
        http://localhost:8080/wordladder?dictname=smalldict1.txt&word1=bee&word2=bog
## 5. serve will deny the request and redirct to a login form
## 6. type "fjj" for User and "123456" for Password
## 7. login success and redirct to the origin request URL

#### ps: make configuration in a unfamiliar environment is so hard that I should make more progress. 
