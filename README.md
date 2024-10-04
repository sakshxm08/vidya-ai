# VidyaAI - Socratic Learning Assistant

## Overview

**VidyaAI** is an innovative teaching assistant designed to facilitate learning through the Socratic method. This project was developed for a hackathon focused on the theme of Socratic Learning. The application leverages advanced AI capabilities to engage users in educational discussions, primarily focusing on Data Structures and Algorithms (DSA). By prompting users with thought-provoking questions, VidyaAI encourages critical thinking and deeper understanding of complex concepts.

**Website**: [vidyaai.netlify.app](https://vidyaai.netlify.app)

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation Guide](#installation-guide)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Socratic Teaching Method**: Engages users by asking questions rather than providing direct answers, fostering a deeper understanding of the subject matter.
- **AI-Powered Responses**: Utilizes advanced AI models to generate contextually relevant questions and responses.
- **User-Friendly Interface**: Built with React and Vite for a smooth and responsive user experience.
- **Chat Functionality**: Users can interact with the AI in real-time, simulating a conversational learning environment.
- **Knowledge Base**: A structured knowledge base that the AI can reference to provide accurate information on DSA topics.

## Technologies Used

- **Frontend**:

  - React
  - Vite
  - Tailwind CSS
  - Axios
  - React Router

- **Backend**:

  - Node.js
  - Express
  - MongoDB (Mongoose)
  - JWT for authentication
  - NVIDIA's NeMo Guardrails for AI interactions

- **AI Framework**:
  - Langchain
  - Custom AI models for Socratic questioning

## Installation Guide

### Prerequisites

- Node.js (version 14 or higher)
- Python (version 3.10.9 recommended)
- MongoDB (for local development)

### Setting Up the Project

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/vidya-ai.git
   cd vidya-ai
   ```

2. **Set Up the Backend**:

   - Navigate to the backend directory:
     ```bash
     cd backend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Create a `.env` file in the backend directory and add your MongoDB URI and other environment variables:
     ```plaintext
     MONGODB_URI=your_mongodb_uri
     FRONTEND_URL=http://localhost:3000
     AI_API_URL=your_ai_api_url
     ```

3. **Set Up the Frontend**:

   - Navigate to the frontend directory:
     ```bash
     cd ../frontend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```

4. **Run the Applications**:

   - Start the backend server:
     ```bash
     cd backend
     npm run dev
     ```
   - Start the frontend application:
     ```bash
     cd ../frontend
     npm run dev
     ```

5. **Access the Application**:
   - Open your browser and navigate to `http://localhost:3000` to access the VidyaAI application.

## Usage

1. **User Registration and Login**:

   - Users can sign up and log in to access personalized learning experiences.
   - Upon logging in, users can start a chat with the AI.

2. **Interacting with the AI**:

   - Users can ask questions related to Data Structures and Algorithms.
   - The AI will respond with questions to guide the user towards finding the answer themselves.

3. **Stopping the Application**:
   - To stop the backend server, use `Ctrl + C` in the terminal where the server is running.

## Contributing

We welcome contributions to improve VidyaAI! If you have suggestions or want to report issues, please open an issue or submit a pull request.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Open a pull request to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Thank you for checking out VidyaAI! We hope this project inspires innovative approaches to learning through the Socratic method. Happy learning!
