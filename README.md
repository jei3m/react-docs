# React-Docs

## Overview

`React-Docs` is a full-stack project that utilizes React JS for the frontend and Firebase for the backend. This application provides a platform for users to register accounts, authenticate, and manage documents with real-time updates and sharing capabilities.

## Features

- **Account Registration & Authentication**: Users can create an account and log in using email/password or Google Sign-In API.
- **Real-Time Document Editing**: Documents can be edited with changes automatically saved in real time.
- **Public Sharing**: Users have the option to make their documents publicly accessible.

## Tech Stack

- **Frontend**: React JS
- **Backend**: Firebase
- **Authentication**: Firebase Authentication, Google Sign-In API
- **Database**: Firebase Firestore (for storing and retrieving documents)

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/react-docs.git
    cd react-docs
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up Firebase:

    - Create a Firebase project and obtain your Firebase configuration details.
    - Add your Firebase configuration to the `src/firebase.js` file.

4. Start the development server:

    ```bash
    npm start
    ```

5. Open `http://localhost:3000` in your browser to access the application.

## Usage

- **Registration & Authentication**:
  - Users can register with their email and password or log in using Google Sign-In.
  
- **Document Management**:
  - Create and edit documents with automatic saving.
  - Toggle the visibility of documents to public or private.


