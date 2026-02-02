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
