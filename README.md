# Missing-Poker-Cards
This is an homework exercise of my Big Data course. In this MapReduce code to you have to find missing poker cards in a deck of 52 cards.

# How to Run:
* Copy Poker Input File.txt to HDFS using command:
```
hadoop fs -put Poker\ Input\ File.txt
```
* Make the .jar file of MissingPokerCards.java
* Run MissingPokerCards.jar file on Poker Input File.txt using the command:
```
hadoop jar MissingPokerCards.jar Poker\ Input\ File.txt output
```


