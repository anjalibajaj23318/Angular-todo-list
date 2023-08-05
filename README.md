# Todo List - Angular Project
This is a simple Angular project that implements a basic Todo List application. The application allows users to add new tasks and delete existing tasks without using local storage. It is developed using Angular CLI version 16.1.8 and requires Node version 18.17.0 and npm version 9.6.7 to be installed.

# Live Demo
You can access the live demo of the application here.

# Features
Add new tasks: Users can add new tasks to the Todo List.
Delete tasks: Users can remove tasks from the Todo List.
# Getting Started
To run the project locally, follow the steps below:

Ensure you have Node.js and npm installed on your machine. You can download them from the official website: Node.js.

Clone this GitHub repository to your local machine using the following command:

bash
Copy code
git clone https://github.com/your-username/your-todo-list-repo.git
Change into the project directory:

bash
Copy code
cd your-todo-list-repo
Install project dependencies using npm:

bash
Copy code
npm install
Run the Angular development server:

bash
Copy code
ng serve
Open your web browser and navigate to http://localhost:4200/ to view the Todo List application.

# Usage
To add a new task, type the task description in the input field provided and press the Enter key or click the "Add" button.
To delete a task, click on the trash icon next to the task you wish to remove.
# Project Structure
The project follows a typical Angular project structure:

css
Copy code
your-todo-list-repo/
  ├── e2e/
  ├── src/
  │   ├── app/
  │   │   ├── components/
  │   │   │   ├── todo-list/
  │   │   │   │   ├── todo-list.component.html
  │   │   │   │   ├── todo-list.component.css
  │   │   │   │   ├── todo-list.component.ts
  │   │   ├── app.component.html
  │   │   ├── app.component.css
  │   │   ├── app.component.ts
  │   ├── assets/
  │   ├── index.html
  ├── angular.json
  ├── package.json
  ├── tsconfig.json
  ├── ...
Contributing
If you want to contribute to this project, feel free to open a new pull request. Contributions, bug reports, and feature requests are always welcome!
