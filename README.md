# Habit Tracker App

> A habit tracking app that will help you to create and maintain an awesome daily and weekly routine, which is one of the most powerful tools for achieving your goals and sending your life into an upwards spiral.

## Technologies Used

1.  NodeJS
2.  Express
3.  EJS
4.  MongoDB

## Installation

##### Clone the latest Repository

`git clone https://github.com/agarwalshashankjan/HabitTrackerNode.git`

##### Into the project directory

`cd HabitTrackerNode`

##### Installing NPM dependencies

`npm install`

##### Then simply start your app

`npm start`

Keep the mongoose server ON and then start the server

#### The Server should now be running at http://localhost:3000/

Check the console for this, if it says connected, the configuration is complete, otherwise resolve the errors:

```
Server started at http://localhost:3000/
Connected to MongoDB successfully!
```

## Folder Structure

HabitTrackerNode <br>
├── assets <br>
│ --- ├── calendar.svg <br>
│ --- └── css <br>
│ -------- └── styles.css <br>
│ -------- └── bootstrap.min.css <br>
├── config <br>
│ --- └── keys.js <br>
├── models <br>
│ --- ├── Habit.js <br>
│ --- └── User.js <br>
├── node_modules <br>
├── routes <br>
│ --- ├── index.js <br>
│ --- └── users.js <br>
├── views <br>
│ --- └── partials <br>
│ -------- └── messages.ejs <br>
│ --- ├── dashboard.ejs <br>
│ --- ├── layout.ejs <br>
│ --- ├── login.ejs <br>
│ --- ├── register.ejs <br>
│ --- └── welcome.ejs <br>
├── .gitignore <br>
├── app.js <br>
├── package.json <br>
├── package-lock.json <br>
└── README.md <br>
