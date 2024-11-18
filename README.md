
# Quizify

**Quizify** is a web-based application that allows users to create quizzes, take quizzes, and view their results. The app is built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js).

---

## Features

- **Create Quizzes:** Design custom quizzes by adding questions and options.
- **Take Quizzes:** Attempt quizzes and see your scores immediately.
- **Quiz Dashboard:** View all available quizzes in a user-friendly interface.
- **Dynamic Routing:** Smooth navigation between components using React Router.
- **Database Integration:** Quizzes and results are stored securely in MongoDB.

---

## Tech Stack

- **Frontend:** React.js, HTML5, CSS3
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Tools:** VS Code, MongoDB Compass, Babel, Git

---

## Installation and Setup

### Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org)
- [MongoDB](https://www.mongodb.com)
- [Git](https://git-scm.com)

### Steps to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/quizify.git
   cd quizify
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up MongoDB:
   - Start your MongoDB server.
   - Create a `.env` file in the root directory and add your MongoDB URI:
     ```env
     MONGO_URI=your_mongodb_connection_string
     PORT=5000
     ```

4. Run the application:
   - Start the backend:
     ```bash
     node server.js
     ```
   - Start the frontend:
     ```bash
     npm start
     ```

5. Open your browser and go to:
   ```
   http://localhost:3000
   ```

---

## Project Structure

```
quizify/
├── node_modules/ (not included in the repo)
├── public/ (not included in the repo)
├── src/
│   ├── components/
│   │   ├── Navbar.js
│   │   ├── Dashboard.js
│   │   ├── QuizTaking.js
│   │   ├── CreateQuiz.js
│   │   ├── QuizDisplay.js
│   ├── App.js
│   ├── App.css
│   ├── index.js
├── package.json (not included in the repo)
├── .env (not included in the repo)
├── README.md
```

---


## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## Contact

For questions or feedback, please reach out via:
- **Email:** nithyagauri@gmail.com
- **GitHub:** angr3yo(https://github.com/angr3yo/)

---

