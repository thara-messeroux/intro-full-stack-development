# Intro to Full Stack Development

This folder is for my learning.

## Why this exists
I am learning how websites work behind the scenes.

## What I’m learning
- How browsers talk to servers
- What frontend and backend mean
- How full stack development fits together

## Notes for myself
Go slow.
Understand first.
Confidence comes from clarity.

## Learning Resources
- Full Stack Basics (MongoDB): https://www.mongodb.com/resources/basics/full-stack-development
- Frameworks vs Libraries (freeCodeCamp): https://www.freecodecamp.org/news/the-difference-between-a-framework-and-a-library-bd133054023f/
- Express.js: https://expressjs.com/
- Node.js: https://nodejs.org/en
- React: https://react.dev/
- Python: https://www.python.org/
- Django: https://www.djangoproject.com/
- PostgreSQL: https://www.postgresql.org/

## Key Takeaways
- A website is made of a frontend, a backend, and a database
- The browser asks for things, and the server responds
- Tools have roles — no single tool does everything

## Concepts

### What “full stack” means (simple)
Full stack development means building or understanding the full system:
- Frontend (what users see)
- Backend (the server logic)
- Database (where data is stored)

### Real-world analogy
A web app is like a restaurant:
- Frontend = dining room (what customers see)
- Backend = kitchen (work happens behind the scenes)
- Database = pantry/inventory (stored information)

### Frontend vs Backend vs Database (simple)
Frontend:
- Everything users see and click
- Buttons, text, images, forms

Backend:
- The logic and decisions
- Checks permissions and rules

Database:
- Stores information long-term
- Users, posts, comments, likes

Example: liking a post
- Frontend: click the like button
- Backend: verifies the action
- Database: saves the like

## Database

A database is where an application stores information permanently so it can be saved, searched, and retrieved later.

### Two Types of Databases

#### 1. Relational Databases
Relational databases store data in tables made of rows and columns. Each row represents one record, and each column represents a specific attribute.

These databases are commonly used when data is structured and consistency is important, such as in banking or payment systems.

Examples:
- MySQL
- PostgreSQL
- Oracle

#### 2. Non-Relational Databases
Non-relational databases store data in more flexible formats such as documents, key-value pairs, or graphs. Each record does not need to follow the same structure.

These databases are useful for applications with large amounts of unstructured or rapidly changing data, such as social media platforms.

Examples:
- MongoDB
- Redis
- Elasticsearch

Relational databases prioritize structure and reliability, while non-relational databases prioritize flexibility and scalability.


## Client / Server Architecture
Client:
- The browser or app the user uses
- Sends requests

Server:
- A computer that receives requests
- Sends responses back

Simple rule:
The client asks.
The server answers.


## Requests and Responses
Request:
- A message sent by the client
- Asking for a page or data

Response:
- The server’s reply
- Includes a result and a status code

Common status codes:
- 200: OK (everything worked)
- 404: Not found (the page does not exist)
- 500: Server error (something broke on the server)

## Frontend Building Blocks
Frontend is everything the user sees and interacts with.

It includes:
- Page structure (text, images, buttons)
- Styling (colors, fonts, layout)
- Behavior (clicks, animations, form feedback)

If users can see it or click it, it is frontend.

## Backend and Database Building Blocks
Backend:
- Handles logic and rules
- Decides what actions are allowed
- Talks to the database

Database:
- Stores information long-term
- Users, posts, comments, likes
- Does not make decisions

Example:
- Backend checks permissions
- Database stores the data



## Frameworks (Plain English)
A framework is a pre-built structure that helps organize an application.
It provides rules, conventions, and tools so developers don’t have to
start from scratch every time.

Frameworks:
- Define how an app is structured
- Handle common tasks (routing, requests, responses)
- Improve speed, safety, and consistency

### Framework vs Library
A framework controls the flow of the application and calls your code.
A library is something you call when you need a specific feature.

### Opinionated vs Unopinionated
- Opinionated frameworks (Django, Rails) enforce a specific structure
- Unopinionated frameworks (Express) offer more flexibility but require
  more decisions from the developer

Frameworks are built on top of programming languages and are used on
both the front-end and back-end of full-stack applications.

## Common Web Development Stacks
A stack is a combination of technologies used together to build a full
web application. Each stack includes tools for the frontend, backend,
and database.

### MEN Stack
- MongoDB (database)
- Express (backend framework)
- Node.js (server runtime)

The MEN stack is commonly used for backend-focused applications and APIs.

### MERN Stack
- MongoDB (database)
- Express (backend framework)
- React (frontend framework)
- Node.js (server runtime)

The MERN stack builds on the MEN stack by adding React to handle the
frontend user interface.

Stacks use different tools, but the responsibilities of frontend,
backend, and database remain the same.


## Python / Django / PostgreSQL Stack
This stack uses Python for backend development, Django as the backend
framework, and PostgreSQL as the database.

- Python is the programming language used on the server
- Django provides structure, rules, and security for backend logic
- PostgreSQL stores data in structured, relational tables

Although the tools are different from the MERN stack, the roles remain
the same:
- The client sends requests
- The backend decides what is allowed
- The database stores information

## Final Mental Model (Full-Stack)
A full-stack application is built from three layers:
- Frontend (client): what users see and interact with
- Backend (server): rules, logic, and security
- Database: long-term data storage

The flow is always:
Frontend asks → Backend decides → Database remembers

Different stacks use different tools, but the responsibilities of each
layer never change. Understanding this model makes it easier to learn
new frameworks, languages, and stacks.

