# Clients and services
[https://clientes-servicios-arep.herokuapp.com/mypage.html](https://clientes-servicios-arep.herokuapp.com/mypage.html)
## URLReader
this programm needs to recieve an argument, this should be of type URL: "https://www.google.com" and the result will be saved in resultado.html, you can open resultado.html in your browser
to run pls

    java -cp networkClient-1.0-SNAPSHOT.jar edu.escuelaing.edu.co.URLReader http://www.google.com

## URLScanner

this program allows to get the protocol, authority, host, port, path, query, file and ref of an specific site url
to run pls

    java -cp networkClient-1.0-SNAPSHOT.jar edu.escuelaing.edu.co.URLScanner


## HttpServer
> to run please run main of bttoServer package
this excercise creates an unique instance of http with a singleton pattern, starts a server in port 35000 and have a socket to listen
every string sended from the url search bar, is allowed to difference between method and path, then for the response is allowed to shearch in the www forlder to render the content invoked in there.

    you can invoke http://localhost:35000/mypage.html to see a beauty image of the universe

this server also is boostraped, you can see the styles in action in:

    http://localhost:35000/album/index.html

to run pls

    java -cp networkClient-1.0-SNAPSHOT.jar edu.escuelaing.edu.co.httpServer.HttpServer


## socket
this program have to different classes, first one is the EchoClient and the other EchoServer, to get in, you must run first the EchoServer and ther the EchoClient, you can send messages from the client and will be recievend and replied with the same message from the server

    ex: input: holas
    output: holas
to run pls

    java -cp networkClient-1.0-SNAPSHOT.jar edu.escuelaing.edu.co.soket.EchoServer
    java -cp networkClient-1.0-SNAPSHOT.jar edu.escuelaing.edu.co.soket.EchoClient

## socketcuadrado
this program will have the same communication from the socket server, but the difference, the client will send a number, will be recieved by the server and will be returned with squared of this number

    ex: input: 2
    output: 4.0

to run pls

    java -cp networkClient-1.0-SNAPSHOT.jar edu.escuelaing.edu.co.socketcuadrado.EchoServer
    java -cp networkClient-1.0-SNAPSHOT.jar edu.escuelaing.edu.co.socketcuadrado.EchoClient






7/sept/2021


## License

MIT

**Nicolás Torres Páez**
**colombia school of engineering Julio Garavito**

