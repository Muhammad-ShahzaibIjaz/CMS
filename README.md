# CMS (Contact Management System)

CMS is a Contact Management System that allows users to efficiently manage their contacts, send emails, make audio and video calls, create groups for chatting, and more. This web application is built using Vue.js for the frontend, Node.js with Express for the backend, and MongoDB for the database.

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Configuration](#configuration)
  - [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Database Schema](#database-schema)

## Features

- User authentication: Sign up, log in, log out.
- Contact Management: Create, edit, delete, and view contacts.
- Emailing System: Send emails to contacts using a custom emailing system.
- Audio Calls: Make audio calls with contacts.
- Video Calls: Make video calls with contacts.
- Group Chat: Create and participate in group chats.

## Technology Stack

- **Frontend**: Vue.js
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Real-time Communication**: WebSocket (for audio and video calls)
- **Authentication**: JSON Web Tokens (JWT)

## Getting Started

To get started with the CMS application, follow the steps below.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cms.git

2. Navigate to the project repository:
    ```bash
    cd cms

3. Install dependencies for both frontend and backend:
    ```bash
    #Install frontend dependencies
    cd frontend
    npm install

    #Install Backend dependencies
    cd backend
    npm install


### Configuration

1. Create a MongoDB database and obtain the connection URI

2. Configure the backend by creating a `.env` file in the backend directory with the following content:
    ```bash
    cd backend
    npm run serve

### Usage

1. Start the backend server:
    ```bash
    cd backend
    npm run serve

2. Start the frontend server:
    ```bash
    cd frontend
    npm run serve

### API ENDPOINTS

### Database Schema

