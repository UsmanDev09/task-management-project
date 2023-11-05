
# Project Title

This project is a Task Management MERN application that has the following features.
1. Add tasks with a title and description
2. View list of tasks
3. Mark tasks as completed
4. Filter tasks by their completion status (completed, not completed)
5. Delete tasks
6. Implement a dark mode for the React application using Context API




## Documentation

I have used Vite App because it is faster than CRA. 

I have written API's in Expressjs, and properly handled errors and well as logging. The folder structure comprises routes, models, controllers and services. 

The frontend state management is done using Context API. Routing is handled through react-router-dom. 



## Installation

Install my-project with npm

```bash
  cd client
  npm install
  npm run dev

  cd server
  npm install
  npm start
```
    
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file in the server directory.

`MONGO_CONNECTION_STRING`

Add another .env in the client directory.

`VITE_SERVER_URL`

For your ease, you can use my mongodb instance since I have seeded some data into it. 

`mongodb+srv://usiddique09:usman@cluster0.grcckce.mongodb.net/`

The `VITE_SERVER_URL` is `http://localhost:3000`

