# full-stack-games-app-hw

1. What is responsible for defining the routes of the `games` resource?
    Express in the create_router.js file.


2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?
     The client is before the server in the folder structure. The client is the front end of the app and is responsible for holding the functionality of the application it handles requests and responses to the server.
	 The server handles the data (json) coming from the database.

3. What are the the responsibilities of server.js?
     It listens for requests being made to the routes it has defined. 

4. What are the responsibilities of the `gamesRouter`?
    The gamesRouter is used in a function and is called to display all the games stored on the database on '/api/games'

5. What process does the the client (front-end) use to communicate with the server? 
    A use command.


6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs
         The optional second argument includes information about HTTP requests made to the database or API. eg, PUT. In this application it is used for  catching an error.

7. Which of the games API routes does the front-end application consume (i.e. make requests to)? 
it makes requests to the client and the server.
    


8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?

    The Mongo DB driver allows us to interact with Mongo DB using promises as it has an  asynchronous API.

## Extension

Why do we need to use [`ObjectId`](https://mongodb.github.io/node-mongodb-native/api-bson-generated/objectid.html) from the MongoDB driver? 
     It is the documents unique identifier.

Add to your diagram the dataflow for removing a game.
