single-thread-messenger
=======================

Java Single Thread Client Server

New application made in java to operate the single thread Socket Program.

The utility is simple  console based on the local machine where the client and server interact on the number doubling game.

Simply the method is to send and receive messages from server and client.

The method is synchronous two way communication.
Now it's a basic need to develop the givem program to many (multiple threads).

Multi threading being the asset of java helps us to achieve the same.

If various processes are acquiring the same socket, we can perform the priority scheduling using the famous algorithms shown below:
 
  > The Famous "Producer Consumer"
    Link:  http://en.wikipedia.org/wiki/Producer%E2%80%93consumer_problem
  
  
  > "The Reader and writer problem"
   
   Link: http://en.wikipedia.org/wiki/Readers%E2%80%93writers_problem
   Basic implementation of Java
   
  > "Mutex and Lock aquisition approach"
    The above feature is utilized by Gtalk to expand the features of group chatting and maintaining a chat room...
    
    Above processes will be implemented in the program with the help of syncronous methods and java multi threading programming
    
    This repository implements the following as a simple two way chat
    
    Implementing on linux:
       1) Make Sure JDK kit is installed
       In a folder download the file
       and run:
        > javac Server.java
        > javac Client.java
      
      2) After that run:
      >java Server (on one cmd window)
      
      >java Client (on other cmd window)
      
      Implementing on Windows:
      >Set path for javac and java in the environmnetal variables
      
      
      Use above commands to initialize the Server and Client socket instructions
      
      The project needs further development mentioned above...
      Please Igonore urls.py~ file.
      
      
