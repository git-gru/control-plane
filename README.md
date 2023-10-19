# CONTROL PLANE

This repository contains the application for the [Reactive DB](https://drive.google.com/file/d/1SVo1QmSaxDv5A7P6lwHGeXMlggJVaNMh/view?usp=sharing).

## Version
- Node.js `v16.20.2`
- MongoDB `v7.0.2`

## How To Run

1. MongoDB Setup
Run the below command in Mongo Shell
```
load("db/connect-and-insert.js")
```

2. Start the Express server:
```
cd server
npm install
npm run dev
```

3. Start the React app (in a new terminal window):
```
cd app
npm install
npm start
```
