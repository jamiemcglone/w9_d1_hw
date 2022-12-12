What is responsible for defining the routes of the games resource?

Server.js uses the createRouter function defined in create_router.js to create the routes.

What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?

The client is responsible for the front end aspects of the app, such as the way that the app handles user input. The server is responsible for managing the backend, such as creating the routes, and building the database.

What are the the responsibilities of server.js?

Server.js connects to the database and sets up the routes, it also gets the server running.

What are the responsibilities of the gamesRouter?

The games router sets up the routes for everything that will be used for games.

What process does the the client (front-end) use to communicate with the server?

Client-server model.

What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs

Then, in this case it translates the data from the fetch into json.


Which of the games API routes does the front-end application consume (i.e. make requests to)?

The / route with the post method.


What are we using the MongoDB Driver for?

It allows node to connect to MongoDB and work with the data in the database.