# Task Tracker

Task Tracker is a React application designed to help you manage your tasks. With its intuitive interface, you can easily list all tasks, toggle task status, add new tasks, and remove existing ones.

This project served as a refresher for my understanding of core React concepts such as components, hooks, props, and routing.

## Features

- **List All Tasks**: View all your tasks at a glance.
- **Toggle Task**: Mark a task as complete or incomplete with a simple toggle.
- **Add New Tasks**: Easily add new tasks to your list.
- **Remove Tasks**: Delete tasks you no longer need with a single click.

## Getting Started

Follow the instructions below to set up the project on your local machine for development and testing purposes.

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed on your system.

### Installation

1. Clone the repository to your local machine.

   ```
   git clone https://github.com/rupesh226/react-task-tracker.git
   ```

2. Navigate to the project directory.

   ```
   cd react-task-tracker
   ```

3. Install all the required dependencies.
   ```
   npm install
   ```

### Running the Backend JSON DB Server

You have two options to start the backend server:

- Using the `json-server` command:

  ```
  json-server --watch db.json --port 5000
  ```

- Or using the npm script:
  ```
  npm run server
  ```

### Running the Frontend Application

To start the frontend React application, run:

```
npm start
```

Your application should now be running on [http://localhost:3000](http://localhost:3000) (or the port you've configured).

---

Enjoy using **Task Tracker** and managing your tasks with ease!
