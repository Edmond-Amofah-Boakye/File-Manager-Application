
File Manager App

## Overview

This is a file manager application built on the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to manage and share their files efficiently.

## Prerequisites

Make sure you have the following software installed on your machine:

- Node.js: [Download Node.js](https://nodejs.org/)
- MongoDB: [Download MongoDB](https://www.mongodb.com/try/download/community)

## Installation

1. Clone the repository:
    git clone https://github.com/Edmond-Amofah-Boakye/File-Manager-Application

2. Navigate to the project directory:
    cd File-Manager-Application
  
3. Install dependencies for the server:
    cd server    -- which is the backend folder
    npm install

4. Install dependencies for the client:
    cd client   -- which is the frontend folder
    npm install

## Configuration

1. Create a `.env` file in the `server` directory and configure the following variables:
PORT=5000
DB_URL= 
etc.


## Database Models
The application uses MongoDB as its database. You can access and manage your data using a MongoDB compass.

├── Structure for the Models
    │
    ├── User Model
    │   ├── name
    │   ├── email
    │   ├── password
    │   ├── picture
    │   ├── role
    │   ├── confirmed
    │   └── active
    │

    
    ├── File Model
    │   ├── Title
    │   ├── Filename
    │   ├── Description
    │   ├── type
    │   ├── file
    │   ├── downloads
    │   ├── emails
    │   ├── createdBy
    │

    
    ├── Token Model
    │   ├── id
    │   ├── confirmationToken
    │   ├── resetPasswordToken
    │   ├── resetPasswordTokenExpiration
    │   
    

1. Start the Backend server:
    - cd server 
    - npm run start or npm start

2. Start the client:
    - cd client
    - npm run dev
  

4. Open your browser and navigate to [http://localhost:5173]to access the File-Manager-Application.

## Usage

- **Uploading Files:**
  - Click the "Upload" button to select and upload files.

- **Managing Files:**
  - View, download, send, or delete files from the file list.

- **Searching:**
  - Utilize the search bar to quickly find specific files.

- **Managing Tasks:**
  - Create, edit, and delete tasks associated with your user account.



    
