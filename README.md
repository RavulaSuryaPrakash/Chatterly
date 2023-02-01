# Chatterly - Real-Time Encrypted Chat & Voice Platform

Chatterly is a secure, real-time chat and voice communication platform built using the **MERN stack** (MongoDB, Express.js, React, Node.js). It supports real-time messaging, group chats, and voice & video calls, ensuring fast and secure communication. The platform leverages **Socket.io** for real-time communication, **Firebase** for push notifications, and **Diffie-Hellman encryption** for secure messaging. It is deployed on **AWS** using **Docker containers** with auto-scaling, load balancing, and CI/CD pipelines.

---

## Features

- **Real-Time Messaging**: Instant messaging with support for one-on-one and group chats.
- **Voice & Video Calls**: High-quality voice and video calls integrated directly into the platform.
- **End-to-End Encryption**: Secure communication using the **Diffie-Hellman key exchange algorithm**.
- **Push Notifications**: Real-time notifications powered by **Firebase**.
- **Scalable Infrastructure**: Deployed on **AWS** using **Docker containers**, with **auto-scaling**, **load balancing**, and **CI/CD pipelines** for seamless updates.
- **40% Faster Communication**: Optimized performance using **Socket.io** and efficient backend architecture.

---

## Technologies Used

### Frontend
- **React.js**: For building the user interface.
- **Socket.io Client**: For real-time communication between the client and server.

### Backend
- **Node.js**: Runtime environment for the server.
- **Express.js**: Framework for building the REST API.
- **Socket.io**: Enables real-time, bidirectional communication.

### Database
- **MongoDB**: NoSQL database for storing user data, messages, and other information.

### Real-Time Communication
- **Socket.io**: Handles real-time messaging and notifications.
- **WebRTC**: Powers voice and video calls.

### Security
- **Diffie-Hellman Encryption**: Ensures secure end-to-end encryption for messages.

### Notifications
- **Firebase**: Sends real-time push notifications to users.

### Deployment
- **Docker**: Containerization for easy deployment and scalability.
- **AWS**:
  - **EC2**: Hosts the Docker containers.
  - **Auto-Scaling**: Automatically adjusts the number of instances based on traffic.
  - **Load Balancer**: Distributes traffic evenly across instances.
- **CI/CD Pipeline**: Automated deployment using **GitHub Actions** or **Jenkins** (specify if applicable).

---