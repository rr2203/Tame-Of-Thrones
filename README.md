# Tame Of Thrones

## Summary
Solution for the golden crown problem coding challenge on geektrust:
Shan, the gorilla king of the Space kingdom wants to rule all Six Kingdoms in the universe of Southeros.

There is no ruler today and pandemonium reigns. Shan is sending secret messages to all kingdoms to ask for their allegiance. Your coding challenge is to help King Shan send the right message to the right kingdom to win them over. Each kingdom has their own emblem and the secret message should contain the letters of the emblem in it. Once Shan has the support of 3 other kingdoms, he is the ruler!

## System Requirements
1. Java 1.11 or above
2. Maven 3.6 or above

## Steps to run the program:
1. Clone the repository
```
$ git clone https://github.com/rr2203/tame-of-thrones.git
```
2. In the root directory execute the following command to install dependencies
```
$ mvn clean install -DskipTests
```
3. In the root directory execute the following command to run the program
```
$ java -jar target/geektrust.jar <path-to-input-file>
```

## Run Tests:
Run tests
Execute following to run the tests:
```
$ mvn test
```

To run specific tests , execute the following command in the root directory
```
$ mvn -Dtest=<TestFileName> test
```




