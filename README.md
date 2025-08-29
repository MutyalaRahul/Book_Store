# Book Store Project (MERN Stack)

## Description
This is a simple Book Store Project built using the MERN (MongoDB, Express.js, React, and Node.js) stack. This project demonstrates basic CRUD (Create, Read, Update, Delete) operations on both the backend and frontend, including routing and CORS policy configuration.



## Features
- **Backend CRUD**: The backend provides CRUD operations for managing books. You can create, read, update, and delete books using the API endpoints.
- **Backend Router**: Express.js is used to set up backend routing. Each CRUD operation has its own route and controller for clean code separation.
- **CORS Policy**: Cross-Origin Resource Sharing (CORS) is configured to allow requests from the frontend to the backend, ensuring proper communication.
- **MongoDB Operations**: MongoDB is used as the database for storing book information. The backend performs database operations such as creating, reading, updating, and deleting records.
- **Frontend CRUD**: The frontend provides a user interface for performing CRUD operations on books. You can add new books, view existing books, edit book details, and delete books.
- **Frontend Router**: React Router is used for client-side routing, allowing seamless navigation between different pages of the frontend application.

## Screenshots
- Home
- Card View
- Create Book
- Show Book
- Edit Book
- Delete Book

## Getting Started
Follow the steps below to set up the project on your local machine and run it:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/RahulMutyala/Book-Store-Project
   cd book-store-project
   ```

2. **Backend Setup**:
   ```bash
   cd backend
   npm install
   ```
   Configure the MongoDB connection by creating a `.env` file with your MongoDB URI:
   ```
   MONGODB_URI=mongodb://localhost:27017/bookstore
   ```
   Start the backend server:
   ```bash
   npm run dev
   ```

3. **Frontend Setup** (in a new terminal):
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

## Technologies Used
### Backend:
- Node.js
- Express.js
- MongoDB

### Frontend:
- Vite
- React

## Contact
If you have any questions, feedback, or would like to connect, feel free to reach out to me.

- **Name**: Rahul
- **Email**: rahulmutyala258@gmail.com

I'm open to collaborations and discussions related to MERN stack development or any other projects.
