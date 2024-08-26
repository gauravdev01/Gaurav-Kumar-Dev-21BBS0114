# Gaurav-Kumar-Dev-21BBS0114
# *Realtime Chess Game*

This project is a turn-based chess-like game implemented with websocket communication, focusing on server-client architecture, real-time communication, and a web-based user interface.

*Getting Started*

These instructions will help you set up the project on your local machine for development and testing purposes.

*Prerequisites*

Make sure you have Node.js installed on your machine. You can download it from [here](https://nodejs.org/en).

*Installation*

Follow these steps to set up the project:

*Open the Command Line*

Start by opening your terminal or command prompt.

*Create a New Directory*
```bash
mkdir realtime_chess
cd realtime_chess
 ```

*Initialize the Project*

Initialize your project with npm:
```bash
npm init
 ```
This will prompt you with a series of steps to add the necessary details.

![image](https://github.com/user-attachments/assets/c298a35d-50ad-4f59-9056-25c15cf89fef)


Here I have selected the endpoint as app.js. You can set it as any name of your wish.

*Install Express*

Install Express.js, which will be used to create the server:
```bash
npm install express --save
```
Now run your server with the command given below.
```bash
node app.js
 ```
Now head over to localhost:5000 to see your pieces in action.

![image](https://github.com/user-attachments/assets/e690ed3f-3149-4a47-9d7b-bee14d9a4e9c)

This is just a simple chess board but we need to make it real-time.

For making our web app real-time we need to communicate between the server and client. For this, we will use socket.io.

Now head over to the terminal install socket.io
```bash
npm install socket.io –save
```
When we run our server we can see the message from the client on the terminal.

Now run your server open it in two different tabs and see the real-time interaction between the client and the server.

After each move, we are sending the position of the board using the fen notation.

