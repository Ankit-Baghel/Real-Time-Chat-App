# **Ankit Baghel Real-Time Chat App**

---

## **Overview**
The **Ankit Baghel Real-Time Chat App** is a full-stack real-time chat application that enables users to communicate instantly with their connections. It leverages **Socket.IO** for real-time communication and follows the **MERN (MongoDB, Express, React, Node.js)** stack for robust and scalable development.

---

## **Features**
- **Real-Time Messaging**: Enables instant communication using Socket.IO.
- **User Authentication**: Secure login and registration system.
- **Set Avatar**: Users can set a profile avatar.
- **Chat Features**: Includes typing indicators, message timestamps, and message input validation.
- **Modular Codebase**: Organized directory structure for scalability and maintainability.

---

## **Directory Structure**

### **Root Directory**
- **README.md**: Project documentation.
- **images/**: Contains images for project documentation or use in the application.

### **Frontend (`public/`)**
- **Main Files**:
  - `package.json`, `yarn.lock`: Dependency management.
  - `.env.example`: Environment variables template.
  - `.gitignore`: Specifies files to be ignored by Git.

- **Static Files (`public/`)**:
  - `index.html`: Entry point for the React application.
  - `manifest.json`: Metadata for Progressive Web App (PWA).
  - `robots.txt`: Configures web crawlers.

- **Source Files (`src/`)**:
  - **App.js, index.js**: Main application files.
  - **index.css**: Global styles.
  - **Assets**: Contains static assets like images or icons.
  - **Components**:
    - `ChatContainer.jsx`: Displays the chat interface.
    - `ChatInput.jsx`: Handles message input.
    - `Contacts.jsx`: Manages user connections.
    - `Logout.jsx`: Logout functionality.
    - `SetAvatar.jsx`: Allows users to set avatars.
    - `Welcome.jsx`: Displays a welcome screen.
  - **Pages**:
    - `Chat.jsx`: Main chat page.
    - `Login.jsx`: Login page.
    - `Register.jsx`: Registration page.
  - **Utils**:
    - `APIRoutes.js`: Centralized API endpoint management.

### **Backend (`server/`)**
- **Main Files**:
  - `index.js`: Entry point for the Node.js server.
  - `package.json`, `yarn.lock`: Dependency management.
  - `.env.example`: Environment variables template.

- **Controllers (`controllers/`)**:
  - `messageController.js`: Handles chat message logic.
  - `userController.js`: Manages user-related actions.

- **Models (`models/`)**:
  - `messageModel.js`: Defines schema for chat messages.
  - `userModel.js`: Defines schema for user data.

- **Routes (`routes/`)**:
  - `auth.js`: Handles user authentication routes.
  - `messages.js`: Manages chat message routes.

---

## **Installation and Setup**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repository-link.git
