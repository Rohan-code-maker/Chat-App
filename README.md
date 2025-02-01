# CHAT APPLICATION API

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : ROHAN KUMAR GUPTA

*INTERN ID* : CT4MKNM

*DOMAIN* : BACKEND WEB DEVELOPMENT

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

## DESCRIPTION OF TASK

The Chat Application API is a backend service designed to provide real-time messaging capabilities for users. This system enables secure and efficient communication between users while ensuring data persistence using **MongoDB**. Additionally, the API includes an email verification system using **Mailtrap**, ensuring that users confirm their accounts before engaging in conversations.

### Project Overview

The project is developed using **Node.js** and **Express.js** for backend development. It leverages **MongoDB** as the database to store user details, chat messages, and authentication tokens. The application also integrates **Socket.IO** for real-time messaging and **Mailtrap** for email verification.

### Technologies Used

1. **Node.js & Express.js:** Backend framework for building API endpoints.
2. **MongoDB & Mongoose:** NoSQL database for storing chat messages and user details.
3. **Socket.IO:** Enables real-time communication between users.
4. **JWT (JSON Web Token):** Used for secure authentication and user authorization.
5. **Mailtrap:** A virtual email system used for user verification emails.
6. **Bcrypt:** Library used for hashing passwords to enhance security.
7. **Nodemailer & Mailgen:** Handles email sending and formatting.

### Features

1. **User Authentication:**
   - Users can register and log in securely.
   - Passwords are encrypted using Bcrypt.
   - JWT tokens are used for authentication and authorization.

2. **Email Verification:**
   - New users receive a verification email via Mailtrap.
   - The system prevents unverified users from logging in.

3. **Real-Time Messaging:**
   - Users can send and receive messages instantly using Socket.IO.
   - Supports private one-on-one chats.

4. **Message Storage:**
   - Messages are stored in MongoDB for historical reference.
   - Users can retrieve past conversations.

5. **API Integration:**
   - The API is designed to be integrated with any frontend application.
   - Follows RESTful principles for easy scalability.

### Working of the System

1. A user registers by providing an email and password.
2. A verification email is sent using Mailtrap.
3. Upon verification, the user can log in and generate a JWT token.
4. The user can start messaging other verified users in real time.
5. Messages are sent via Socket.IO and stored in MongoDB for retrieval.
6. Users can retrieve their chat history from the database.

### How to Use

1. Clone the repository and install dependencies:
   ```bash
   npm install
   ```
2. Set up a `.env` file with MongoDB connection string and Mailtrap credentials.

3. Start the API server:
   ```bash
   npm run dev
   ```
4. Access the API documentation at `http://127.0.0.1:8080/docs`.

5. Example request to register a new user:
   ```bash
   curl -X POST "http://127.0.0.1:8080/register" -H "Content-Type: application/json" -d '{"email":"user@example.com", "password":"securepassword"}'
   ```

### Example API Response

```json
{
  "message": "Registration successful! Please check your email for verification.",
  "success": true
}
```

### Conclusion

This Chat Application API is a scalable and secure system designed to facilitate real-time messaging between users. By integrating MongoDB for data storage and Mailtrap for email verification, the system ensures a smooth user experience. Future improvements could include group messaging, multimedia support, and AI-powered chatbots for enhanced user interaction.

# OUTPUT

Upon running the API and making a request, the system will:
- Register a user and send an email for verification.
- Authenticate users using JWT.
- Enable real-time chatting through Socket.IO.
- Store and retrieve chat messages from MongoDB.

![Image](https://github.com/user-attachments/assets/ac03be37-01d7-4f22-98b4-2050a85e93bd)

![Image](https://github.com/user-attachments/assets/71205313-4519-4cc0-a14b-595f78b03fd3)

