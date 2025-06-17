# Angular Node CRUD App

A full-stack CRUD (Create, Read, Update, Delete) web application built using:

- **Frontend**: Angular
- **Backend**: Node.js + Express
- **Database**: MySQL

This app demonstrates how to perform basic CRUD operations with a responsive UI, RESTful APIs, and database integration.

## Features

- Add, view, update, and delete records
- REST API with Express and MySQL
- Angular frontend with routing and service integration
- Proxy configuration for smooth API calls during development

## Project Structure

angular-node-crud-app/
├── client/ # Angular frontend
└── server/ # Node.js backend

## 🚀 Project Setup

## Step 1: Install Dependencies


Navigate to both `client` (Angular) and `server` (Node.js) folders and install dependencies:


### Install Angular dependencies

cd client
npm install
### Or use --force if needed:
### npm install --force

### Install Node.js backend dependencies
cd ../server
npm install
### Or use --force if needed:
### npm install --force

## Step 2: Run the Frontend (Angular)

cd client
ng serve

Then open your browser at http://localhost:4200

## Step 3: Run the Backend (Node.js + Express)
### 💻 For Linux/Mac:

cd server
node index.js

### 🪟 For Windows (PowerShell or CMD):

cd server
node index.js
Make sure your index.js file is your server entry point. If you're using a different file (e.g., app.js), replace index.js with that.

Optional: Use Nodemon for Auto-Reload (Dev Only)

npm install -g nodemon
nodemon index.js
