# Event Management Platform Challenge Solution

This repository contains the solution for the Event Management Platform (EMP) coding challenge. It demonstrates the ability to design and implement a clean, efficient, and well-structured backend service using Node.js and TypeScript.

## Overview

The EMP allows users to perform CRUD operations on events. Each event has properties like id, eventName, eventDate, organizer, email, phone, location, createdAt, and updatedAt.

## Getting Started

To get started, clone this repository and follow these steps:

1. Install dependencies: `npm install`  `'pm init -y`  and `npm install express  cors body-parser @types/node @types/express --save`
`npm install typescript ts-node-dev --save-dev`
2. Run the server: `npx tsc`  and `node dist/server.js`


## API Endpoints

### POST /events
Creates a new event.  
URL = http://localhost:3000/events

### PUT /events/:id
Updates an existing event by ID.
URL = http://localhost:3000/events/id

### DELETE /events/:id
Deletes an event by ID.

### GET /events/:id
Retrieves an event by ID.

