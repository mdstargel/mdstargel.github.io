# Data Transfer

[Back to Portfolio](./)

<h2 style="font-size: 30px">Client Server Data Transfer</h2>

-   **Class: Applied Networking (CSCI 332)** 
-   **Grade: A** 
-   **Language(s): C++** 
-   **Source Code Repository:** [mdstargel/client-server-project](https://github.com/mdstargel/client-server-project)  
    (Please [email me](mailto:mdstargel@csustudent.net?subject=GitHub%20Access%20-%20Client%20Server%20Project) to request access.)
\
\
    Click [here](https://youtu.be/xZHdO_LU_BY/) for the demonstration video.


## Project description

This program creates a UDP server side and client side terminal able to send or receive files over the same network. By sending the file line by line over from the server side, it sends and outputs the file on the client side named the same thing with the timestamp. It will not work if the document doesn’t exist.

## How to compile and run the program

Compile and Run (in two seperate terminals):
```bash
g++ udpTestServer.cpp && ./udpTestServer.out
```

```bash
g++ udpTestClient.cpp && ./udpTestClient.out
```

## UI Design

The user can set up a server with a listening port to receive a file. The client enters the server port, server IP address, and the name of the file he/she wishes to send. If the file does not exist an error message will be shown.

![Start](images/trans_start.jpg)  
Fig 1. Start of File Transfer.

![Success](images/successful.jpg)  
Fig 2. Successfull File Transfer.

![File DNE](images/file-not-found.jpg)  
Fig 3. File Not Found Error Message.

![Quit](images/quit.jpg)  
Fig 4. Quit Before Transfer.

## 3. Additional Considerations

- The program outputs the part files as they are being sent or received to both terminals.

[Back to Portfolio](./)
