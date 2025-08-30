# Payzip

**Payzip** is a full-stack mock payment application designed to offer a secure and seamless payment experience. Built with modern web technologies, Payzip enables users to sign up, sign in, send money to other users, and check their available balance, all within an intuitive and responsive interface. With robust user authentication, state management, and real-time communication between the front and back end, Payzip provides a comprehensive demonstration of a secure and user-friendly payment platform.

## Features

- **User Authentication**: Secure authentication using JWT (JSON Web Tokens) for managing user sessions.
- **Sign Up and Sign In**: Users can sign up or sign in to access the application's features.
- **OTP-based Verification**: OTP authentication during signup with OTPs expiring in 2 minutes, and a feature to resend OTPs.
- **Send Money**: Users can securely send money to other registered users.
- **Balance Check**: Users can view their current balance.
- **User Profile Management**: Functionality for users to update their personal details and change their password.
- **Email Integration**: Uses Nodemailer for sending OTPs and EmailJS for handling inquiry emails.
- **Responsive Design**: Fully responsive interface with smooth animations for an enhanced user experience.
- **State Management**: State is managed efficiently with Redux Toolkit, consolidating state logic and reducing code complexity.
- **Animations**: Smooth animations implemented using Framer Motion for an engaging user experience.

## Technologies Used

- **React JS**: For building the user interface.
- **Node.js**: For server-side logic.
- **Express.js**: For creating the backend API.
- **MongoDB**: For the database.
- **JWT (JSON Web Tokens)**: For secure user authentication.
- **Axios**: For handling API requests between the front end and back end.
- **Tailwind CSS**: For designing a responsive and modern user interface.
- **Framer Motion**: For animations and visual enhancements.
- **Nodemailer**: For sending OTP emails.
- **EmailJS**: For handling incoming inquiry emails.
