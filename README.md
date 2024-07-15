# Todo-List

This project is a comprehensive Todo List application built using EJS templating and MongoDB. The application displays the current day and dynamically renders a todo list where users can manage their tasks. The todo list functionality includes options to add, check off, and delete items, all of which are persistently stored in a MongoDB database.

## Features

- **Dynamic Day Display**: The application shows the current day at the top of the todo list, dynamically rendered using EJS.
- **CRUD Operations**: Users can create, read, update, and delete todo list items:
  - **Add Items**: Users can add new todo items to the list.
  - **Check Off Items**: Users can mark items as completed by checking them off.
  - **Delete Items**: Users can remove items from the list.
- **Persistent Storage**: All todo list items are stored in MongoDB, ensuring data persistence across sessions.

## Custom Lists

- **User-Specific Lists**: Users can create their own custom todo lists by appending a unique name to the URL. For example, navigating to `/customlistname` will generate a new custom list stored in the database.
- **Access Custom Lists**: Users can access their custom lists by entering the same URL (`/customlistname`).

## How to Use

1. **Run the Application**: Ensure you have Node.js and MongoDB installed. Run the application locally by executing:
    ```bash
    npm install
    npm start
    ```
2. **Navigate to the Home Page**: Open your browser and go to `http://localhost:3000/` to view the default todo list.
3. **Create Custom Lists**: To create and access a custom list, navigate to `http://localhost:3000/yourcustomlistname`.

## Technologies Used

- **Node.js**: Backend runtime environment.
- **Express.js**: Web framework for Node.js.
- **EJS (Embedded JavaScript)**: Templating engine used for rendering dynamic content.
- **MongoDB**: NoSQL database used for storing todo list items.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB and Node.js.
- **HTML/CSS**: Frontend structure and styling.

## Directory Structure

```plaintext
.
├── public
│   └── css
│       └── styles.css    # Custom CSS for styling the application
├── views
│   ├── list.ejs          # EJS template for the main todo list page
│   └── header.ejs        # EJS template for the header information
|   └── about.ejs         # EJS template for the about section
|   └── footer.ejs        # EJS template for the footer information
├── .gitignore            # Files and directories to ignore in git
├── app.js                # Main application file
├── package.json          # Project dependencies and scripts
└── README.md             # Project documentation

```
![image](https://github.com/user-attachments/assets/da95b6f7-cec2-4b90-86aa-b5e367697594)


