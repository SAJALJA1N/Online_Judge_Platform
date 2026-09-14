# Online Judge Platform

A comprehensive, full-stack **Online Judge Platform** designed for developers and students to practice coding, test algorithms, and manage programming challenges. The platform includes a robust backend API and a responsive, modern frontend interface.

## 🚀 Key Features

*   **Coding Environment**: Interactive workspace for writing and testing code.
*   **User Management**: Secure authentication system (login/registration) using JWT and cookies.
*   **Scalable Architecture**: Decoupled frontend and backend for better performance and maintainability.
*   **Modern Tech Stack**: Built with high-performance frameworks and libraries.
*   **AI-Integrated**: (Optional/Project-specific) Uses Google's Generative AI for advanced features.

## 🛠 Tech Stack

### Frontend
*   **Framework**: React.js
*   **Build Tool**: Vite
*   **Styling**: Tailwind CSS
*   **Routing**: React Router DOM
*   **Communication**: Axios for API interaction

### Backend
*   **Runtime**: Node.js (Express.js)
*   **Database**: MongoDB (via Mongoose)
*   **Authentication**: JSON Web Tokens (JWT), Bcrypt.js
*   **AI Integration**: Google Generative AI SDK
*   **Middleware**: CORS, Cookie Parser

## ⚙️ Project Structure

*   `frontend/`: React application using Vite and Tailwind CSS.
*   `backend/`: Express.js server handling APIs, authentication, and database connectivity.
*   `onlinecompiler/`: Core engine for code compilation and execution.

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- MongoDB instance

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SAJALJA1N/Online_Judge_Platform.git
   cd Online_Judge_Platform
   ```

2. Setup Backend:
   ```bash
   cd backend
   npm install
   # Create a .env file with your DATABASE_URL, JWT_SECRET, and AI_API_KEY
   npm run dev
   ```

3. Setup Frontend:
   ```bash
   cd ../frontend
   npm install
   npm run dev
   ```

## 📝 License
This project is open-source and available under the MIT license.

---
*Built with ❤️ by SAJALJA1N*
