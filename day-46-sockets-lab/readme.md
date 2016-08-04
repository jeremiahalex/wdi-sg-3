# Build a Realtime app

## Introduction

> ***Note:*** _This can be a pair programming activity or done independently._

With websockets, we've seen an alternative to HTTP that we can use to exchange data between a client and a server.  

For this lab, you're going to build a chat app using websockets with Express.  Follow the requirements below and use the starter code to get started - you'll also be using jQuery and AJAX within your application to make this work.

## Exercise

#### Requirements

- Setup the Express app to listen to sockets
- A socket message from the client should contain a name and the text for the message
- Your app should have a `/message` endpoint that creates a new message and sends that message to all of your sockets subscribers
  - If a message is empty, respond with a 400 response and an appropriate message to the console
  - If a message has been accepted, respond with a 200 response and display the message to the page
- The page should keep a running history of your chat

**Bonus:**

- Add a participants list that pulls from the names associated with the messages

#### Deliverable



![Screenshot](http://s21.postimg.org/5k2hri1h3/Screen_Shot_2015_08_12_at_18_44_28.png)

## Additional Resources

- [Socket IO website](http://socket.io/)
