# Notebook Application

A React Native mobile application for creating and managing text, checklist and image notes. Notes are stored locally using AsyncStorage and can be synchronized with an Express.js REST API backed by SQLite.

## Features

- Create, edit and delete notes
- Support text, checklist and image notes
- Search notes by title or content
- Move deleted notes to the recycle bin
- Store notes locally using AsyncStorage
- Synchronize notes with the backend server

## Technology Stack

- React Native
- TypeScript
- Node.js and Express.js
- SQLite
- RESTful API
- AsyncStorage

## Installation

Make sure Node.js, JDK 17 and Android Studio are installed.

```bash
git clone https://github.com/alexyap14/Notebook_Application.git
cd Notebook_Application
npm install --legacy-peer-deps
npm start
```

Open another terminal and run:

```bash
npm run android
```

## Backend Setup

```bash
cd server
npm install
node generateDB.js
npm start
```

The backend runs on port `5000`. The server address used by the mobile application can be configured in `server/Config.js`.

## Contributors

Developed as a team-based academic project.
