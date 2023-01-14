# Tame Of Thrones

## Summary
Solution for the golden crown problem coding challenge on geektrust:

Shan, the gorilla king of the Space kingdom wants to rule all Six Kingdoms in the universe of Southeros.

There is no ruler today and pandemonium reigns. Shan is sending secret messages to all kingdoms to ask for their allegiance. Your coding challenge is to help King Shan send the right message to the right kingdom to win them over. Each kingdom has their own emblem and the secret message should contain the letters of the emblem in it. Once Shan has the support of 3 other kingdoms, he is the ruler!

Each kingdom has an animal emblem and Shan needs to send a message with the animal in the message to win them over.
SPACE emblem - Gorilla, 
LAND emblem - Panda, 
WATER emblem - Octopus,
ICE emblem - Mammoth,
AIR emblem - Owl, 
FIRE emblem - Dragon.

Your coding challenge is to have King Shan send secret message to each kingdom and win them over.
Once he wins 3 more kingdoms, he is the ruler! The secret message needs to contain the letters of the animal in their emblem.
For example, secret message to the Land kingdom (emblem: Panda) needs to have the letter 'p', 'n', d'at-least once and 'a' at-least twice. If he sends 'ahdwvnxxxautup" to the Land kingdom, he will win them over.
King Shan wants to make sure his secret message is not found by his enemies easily. So he decides to use the oldest of the ciphers 'Seasar cipher'. A cipher is a type of secret code, where you swap the letters around so that no-one can read your message.
<img width="959" alt="Screenshot 2023-01-13 at 9 57 04 PM" src="https://user-images.githubusercontent.com/30201131/212447734-46f8b423-5599-47c6-87a2-3e2f9383bd1b.png">

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




