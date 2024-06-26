# 🔐 Authentication and Security

In this series, I explored various levels of authentication and security measures, building up to OAuth. Below are the key concepts covered in this first part:

## Key Concepts

1. **Basic Authentication (Email and Password)**
    - The simplest form of authentication.
    - **Implementation Details**: 
        - Securely storing passwords using best practices.
        - Ensuring passwords are never stored in plain text.

2. **Encryption and Hashing**
    - Understanding the fundamental differences between encryption and hashing.
    - **Implementation Details**: 
        - Using secure password hashing algorithms like bcrypt.
        - Implementing encryption for sensitive data.

3. **Salting Passwords**
    - Enhancing password security by adding salt.
    - **Benefits**:
        - Improving resistance against rainbow table attacks.
        - Ensuring unique hashes for identical passwords.

4. **Cookies and Sessions Management**
    - Using cookies to store session information securely.
    - **Best Practices**: 
        - Implementing secure and HttpOnly flags.
        - Managing session expiration and renewal.

5. **Environment Variables**
    - Securely managing sensitive information using environment variables.
    - **Best Practices**:
        - Avoiding hardcoding secrets in the source code.
        - Using tools like dotenv to manage environment configurations.

6. **Google OAuth Credentials Setup**
    - Setting up Google OAuth credentials for authentication.
    - **Steps**:
        - Configuring the OAuth consent screen.
        - Generating client ID and client secret.

7. **Implementing "Sign In with Google"**
    - Integrating Google Sign-In into the application.
    - **Handling**:
        - OAuth tokens and user sessions.
        - Ensuring secure token storage and management.

## 📦 Dependencies

This project relies on the following dependencies:

- **body-parser**: Middleware to parse incoming request bodies.
- **ejs**: Embedded JavaScript templating for rendering dynamic content.
- **express**: Fast, unopinionated, minimalist web framework for Node.js.
- **pg**: PostgreSQL client for Node.js for database interactions.

## 📧 Contact

Feel free to contact me for any questions or suggestions:

- Email: [iav2020@hotmail.com](mailto:iav2020@hotmail.com)

## 🔗 Project Link

Explore the project on GitHub: [learning-authentication1.4](https://github.com/warszawa1/learning-authentication1.4)




https://github.com/Warszawa1/learning-authentication1.4/assets/48474962/3b826da6-75be-4dbf-b35b-33ce3b5d227b

