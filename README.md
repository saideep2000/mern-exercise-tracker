# Todo list - React App

This was done using ❤️ towards full-stack

## Project

In the project, we have:

### `Features`

1. We will take todos with the text input and a button to get it registered.\
2. When ever the task is done we can click on the radio button as completed.
3. There is a button to remove the todo which are done.
4. There is a live count which tells us the todo left to be completed.
5. Our website will keep track of all the todos we registered, we will can reload to check wheather it's storing in the local_storage or not.

**Note: this is just a website made as a `practice`, towards REACT!**

## Process of project done

folder name - mern-excercise-tracker
(npx create-react-app)
All the backend is in separate folder
(mkdir backend)
In the backend (cd backend):
npm init -y
npm install express cors mongoose dotenv
here cors(ajex request - access out the server from the server), mongoose(mongo db to node), dotenv(load env variables - stored in the file)
(install node globally, node.js)
sudo npm install -g nodemon

To run the node:
nodemon server

Models:
exercise model, user model.

Testing backend (Postman or Insonmia):
1. POST : http://localhost:5001/users/add 
{
    "username": "beau"
}

2. GET : http://localhost:5001/users/

3. POST : http://localhost:5001/exercises/add
{
    "username": "beau",
    "description": "run",
    "duration": "9",
    "date": "2019-05-29T02:22:49.052Z"
}

4. GET : http://localhost:5001/exercises/

5. GET : http://localhost:5001/exercises/650358859b88c36ffec7f2a3

6. POST : http://localhost:5001/exercises/update/650358859b88c36ffec7f2a3
{
    "username": "beau",
    "description": "walk",
    "duration": 120,
    "date": "2019-05-29T02:22:49.052Z"
}

7. DELETE : http://localhost:5001/exercises/650358859b88c36ffec7f2a3

Frontend:



### Things Used

We have used UseState, UseRef, UseEffect

Moreover we use uuid for making random unique id's so that the todos stay unique.

(https://youtu.be/7CqJlxBYj-M)

# react_todolist
