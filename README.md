# PC Builder - Custom PC Ordering System

**PC Builder** is a full-stack web application that enables users to build custom PCs by selecting individual components or choosing from a curated list of pre-built systems. The system integrates a secure payment gateway, interactive educational content, and a robust administrative dashboard for managing orders, users, and inventory.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [Folder Structure](#folder-structure)
- [Usage](#usage)
- [Testing and Security](#testing-and-security)
- [Conclusion](#conclusion)
- [References](#references)

---

## Overview

PC Builder provides a comprehensive solution that simplifies the custom PC building process. Whether you're a tech enthusiast looking to optimize every component or a casual user wanting a hassle-free pre-built system, PC Builder offers:

- **Custom PC Builder:**  
  Create a personalized configuration by selecting components (CPU, GPU, RAM, Storage, PSU) with real-time compatibility checks.
  
- **Pre-Built PC Showcase:**  
  Browse through curated categories such as *Gaming Beast*, *Content Creator*, and *Budget Gamer* for ready-made PC solutions.
  
- **Secure Payment Processing:**  
  Complete your purchase through an integrated payment gateway that handles transactions securely.
  
- **Educational Content:**  
  Access detailed tutorials and guides in the "Learn" section to better understand PC components and assembly.
  
- **Robust Administration:**  
  A dedicated admin dashboard lets administrators manage users, orders, feedback, and product listings efficiently.

---

## Features

- **Interactive Customization:**  
  Users can design their own PC by selecting and validating individual components.
- **Pre-Built Offerings:**  
  Multiple categories of pre-built PCs make it easy for customers to quickly select a system that meets their needs.
- **Integrated Payment System:**  
  Secure transaction processing with real-time validation and digital invoice generation.
- **User-Friendly Interface:**  
  Modern, responsive design built with React and Tailwind CSS to ensure an excellent user experience.
- **Admin Dashboard:**  
  A comprehensive backend for managing users, orders, feedback, and product inventory, complete with dynamic product management features.
- **Scalability and Security:**  
  Built with the MERN stack, ensuring scalability, fast performance, and robust security features such as JWT authentication and bcrypt password encryption.

---

## Technologies Used

- **Frontend:**  
  - React, Tailwind CSS, Recoil, React Router, Axios
- **Backend:**  
  - Node.js, Express, MongoDB, Mongoose
- **Additional Tools:**  
  - GitHub Actions for CI/CD  
  - JWT for authentication  
  - bcrypt for password hashing

---

## Installation and Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/pc-builder-project.git
   cd pc-builder-project

## Setup Environment Variables:

Backend: Create a .env file in the backend folder with:
  ```bash
  MONGO_URI=your_mongodb_connection_string
  JWT_SECRET=your_jwt_secret
  EMAIL_USER=your_email@example.com
  EMAIL_PASS=your_email_password
```
Frontend: (If needed) Create a .env file in the frontend folder for environment-specific variables (e.g., REACT_APP_ADMIN_PASSWORD).

## Install Dependencies:

For the backend:
```bash
cd backend
npm install
```

For the frontend:
```bash
cd ../frontend
npm install
```
