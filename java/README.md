# Java base pack

This folder contains a very minimal, lightweight hello world application that can be built, tested, packaged, and run with Maven tool.

## Prerequisites

Clone this repository from git. You do not need to fork it or send your code anywhere, just clone the code for the live coding exercise.

You should have both Java runtime environment and Java compiler installed, as well as Maven tool. Java version does not matter much, as long as it is at least Java 11. The most important thing is that your installation is set up so you can compile, test, and run Java code.

You probably want to have an IDE installed, any of them will work, but if you want a suggestion, we would recommend IntelliJ Idea Community Edition or VS Code. If you already love Netbeans, Eclipse, Emacs, Vi, or have written your own IDE, by all means bring that along.

## Am I ready for the interview?

You are ready for interview, when you can run these operation, either from a command line or from your favourite IDE:

```sh
./mvnw compile
./mvnw test
./mvnw package
./mvnw exec:java -Dexec.mainClass=exercise.HelloWorld
java -jar target/exercise.jar
```

Done with all that! Congratulations! Now we can start coding immediately with your working environment. If you want to prepare for the interview, brush up on your basic Java and unit test skills a bit, then come with a relaxed attitude. Purpose is not to do any challenging coding, purpose is just to chat by some code, to get to know each others as coders. It's like fireside chat - just with less fire and more Java hopefully!
