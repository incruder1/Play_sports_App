<h1 align="center">Playo App</h1>

<h3 align="center">
The Playo App using the MERN stack (MongoDB, Express, React, Node.js) that help sports enthusiast to connect and attend event.</h3>

<br />

<h2 align="center">🖥️ Tech Stack</h2>


<h4 align="center">Frontend:</h4>

 
![2](https://github.com/user-attachments/assets/b920f681-b5e7-4d84-827c-a1efce652247)
 
<br />

![1](https://github.com/user-attachments/assets/6c5869d2-1b64-4930-a632-9c479a4dc951)
<br />

## Screens ( All screens are responsive along with Dark Mode)
- Homepage / Landing Page
- User Login and Register Page
- Event create Page
- Requests received Page
- Requests sent Page


<br />


## 🚀 Features
- Authentication: Users can sign up and log in to the platform, and their credentials are securely stored in a MongoDB database using encryption.
- Event creation: Authenticated users can create events with a name, short description, timings, number of players limit etc.
- Users can search or filter through listed events to find a suitable event for them.
- Users can request to join the event if the player limit is not full.
- Accepted users can see who all are joining the game.
- Users can view the list of events they have been accepted to or have requested for.
- All pending requests expire after the game starts.
<br/>

## Technologies used
- MongoDB: a NoSQL database used to store data in a JSON-like format.
- Express: a Node.js framework used for building web applications.
- React: a JavaScript library used for building user interfaces.
- Node.js: a JavaScript runtime used for building server-side applications.
- JWT: JSON Web Tokens used for user authentication.
- bcrypt: a library used for password hashing and encryption.

<br/>

## Contributing
If you find any bugs or would like to contribute to this project, please feel free to submit a pull request or open an issue.



<br />

## Glimpses of iBlog 🙈 :


 
<br />

### Tools used on this project

- Visual Studio Code
- Vite-JS template

<br />

# REST API

This repository contains a REST API built using NodeJS, ExpressJS and MongoDB. It follows the REST architecture principles and is designed to be scalable and maintainable.

## Getting Started

Deployed Link :- https://tough-ant-vestments.cyclic.app

## API Endpoints

The following API endpoints are available:

| Endpoint | Method | Description |
| -------- | ------ | ----------- |
| /users/login | POST | Login a user |
| /users/register | POST | Create a new user |
| /events | GET | Get all events |
| /events/:id | GET | Get a single Event |
| /events/send/:eventId | POST | Send a join request |
| /events/accept/:requestId | POST | Accept a join request |
| /events/recieved | GET | Get all recieved requests |
| /events/sent | GET | Get all sent requests |

 
