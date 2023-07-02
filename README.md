Prashant Singh, 
Bachelor of Technology 2024,
IIT(ISM) Dhanbad 

# INTRODUCTION TO PROJECT 

## TASK
To create a website where you can connect with your friends and have a one-to-one video chat with them. It would be fun and you will get to understand how we can send video streams through a connection.
  
# Tech-stack

-	Node–v16.16.0
-	Express JS –v4.17.1
-	Socket.io –v3.1.1
-	Nodemon –v2.0.7
-	React JS –17.0.1
-	Material UI –v4.11.2
-	Peer JS –v1.3.1
-	Yarn –v1.22.10
-	VS Code –v1.75

# OVERVIEW OF THE PROJECT

## LiveCall
A one-on-one web development project to connect two remote users directly to one another via video/audio streams.

It uses the built-in browser capabilities to connect users to one another by only needing of Caller ID which can be extracted from the home page.

Using SOCKET IO allows the server to push updates to the client and vice versa thereby creating a bidirectional event-based connection using WS and WSS (web socket secure protocol).


# PROJECT IMPLEMENTATION


- The project source code document can be divided into two parts, 
1. The server end
2. The client's end

- The server end has its code in server.js which initiates the WebSocket using socket.io creating a bidirectional server that can emit and take in data.
- The client-side is placed in the frontend folder which is a create-react-app layout. The app.js within the “src” folder includes the overall frontend designed using React (HTML, CSS, JS), and it also includes the scrips that connect the frontend to the server using the socket connections.
- The stream (audio + video) is cached and displayed here.
- Two users can then connect via it.


# HOW TO GET THE PROJECT UP AND RUNNING

## Downloading dependencies

1. Open the bash terminal in the root directory.
2. Execute command-
 - npm install
- This will install the dependencies for server files.
3. Now move to the frontend folder using the command-
 - cd front end
4. Now to install further dependencies use-
 - npm install 

## Launching the app

1. Open two bash terminals in the root directory.
2. In the first on execute-
 - npm start
- This will start the server by default listening at port 5000.
3. In the second terminal execute-
 - cd frontend
 - npm start
- This will launch our react app in its default 3000 port.
4. Visit  http://localhost:3000/ in your native browser to access the site.


# Future Enhancements

- Adding a chat box alongside the usual audio/video stream, to enhance the overall productivity of the site.

- Adding a better UI/UX on the website for minor functionalities like remote stream panning and zooming.

- Adding features like screen share to give the site a better shape as a real-time communication portal.

           
