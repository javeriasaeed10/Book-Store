# Book Store App 📚

A full-stack **MERN** application for managing a book store. This project is built using **React Vite** for the frontend and **Node.js** for the backend, with **MongoDB** as the database.

## Features 🚀

- **Frontend**:
  - Built with React Vite for a faster and optimized development experience.
  - Responsive and user-friendly UI.
  
- **Backend**:
  - RESTful API built with Node.js and Express.
  - Secure interaction with the MongoDB database.

- **Database**:
  - MongoDB for data persistence and scalability.

---

## Getting Started 🛠️

### Prerequisites
Ensure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/try/download/community)

---

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/javeriasaeed10/book-store.git
   cd book-store
   ```

2. **Install Dependencies**:

   - Frontend:
     ```bash
     cd frontend
     npm install
     ```

   - Backend:
     ```bash
     cd ../backend
     npm install
     ```

3. **Set up Environment Variables**:
   Create a `.env` file in the `backend` directory with the following:
   ```env
   PORT=5000
   MONGO_URI=<your-mongodb-connection-string>
   JWT_SECRET=<your-jwt-secret>
   ```

---

### Running the Application

1. **Start MongoDB**:
   Ensure your MongoDB server is running locally or provide a cloud connection string.

2. **Run Backend Server**:
   ```bash
   cd backend
   npm run dev
   ```

3. **Run Frontend**:
   ```bash
   cd frontend
   npm run dev
   ```

4. **Access the Application**:
   Open your browser and navigate to:
   ```
   http://localhost:5173
   ```

---

## Project Structure 📂

### Frontend (`frontend/`)
- **React Vite**: A blazing fast React setup.
- **Libraries Used**:
  - Axios for API calls.
  - React Router for routing.

### Backend (`backend/`)
- **Node.js** and **Express**: For building the RESTful API.
- **Libraries Used**:
  - Mongoose for MongoDB integration.
  - bcrypt.js for password hashing.
  - jsonwebtoken for authentication.

---

## Screenshots 🖼️

*Add screenshots or GIFs of your application here.*

---

## Future Enhancements 🌟

- Implement user roles (admin, customer).
- Add search and filter functionality for books.
- Enhance UI with more animations.
- Deploy the app using services like Heroku, Vercel, or AWS.

---

## Contributing 🤝

Contributions are welcome! Feel free to submit a pull request or open an issue to discuss changes.

---

## License 📜

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## Acknowledgments 🙏

- Inspired by the need for efficient book management systems.
- Thanks to the open-source community for tools and guidance.
