# BookSlot - Booking App

## Overview

BookSlot is a full-stack booking application developed using the MERN stack. The app features real-time booking management, search and filtering functionalities, secure user authentication, and payment integration. Stripe is used for payments, and Cloudinary handles image uploads. Tailwind CSS is utilized for a responsive and modern UI design.

![BookSlot](https://github.com/user-attachments/assets/0bb6a58b-6a96-452f-8b11-bc002c4d477b)

## Features

- **Real-Time Booking Management**: Manage bookings and receive notifications in real time.
- **Search and Filtering**: Search and filter available slots and bookings easily.
- **Secure Authentication**: User authentication through Email.
- **Payment Integration**: Secure payment processing using Stripe.
- **Image Management**: Efficient image uploads and management with Cloudinary.
- **Responsive Design**: Modern and responsive UI with Tailwind CSS.

## Technologies Used

- **Frontend**:
  - React.js
  - Tailwind CSS

- **Backend**:
  - Node.js
  - Express.js
  - JWT

- **Database**:
  - MongoDB

- **Authentication**:
  - Email

- **Payment Processing**:
  - Stripe

- **Image Management**:
  - Cloudinary

## Getting Started

### Prerequisites

- Node.js
- npm
- MongoDB

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/abhishek751982/BookSlot.git
    cd AbhiBook
    ```

2. **Install server dependencies**:
    ```bash
    cd backend
    npm install
    ```

3. **Install client dependencies**:
    ```bash
    cd frontend
    npm install
    ```

### Configuration

1. **Set up environment variables**:
   Create a `.env` file in the `AbhiBook` directory with the following content:

    ```env
    MONGODB_CONNECTION_STRING
    JWT_SECRET_KEY= abhishek
    FRONTEND_URL=
    
    # Cloudinary Variables
    CLOUDINARY_CLOUD_NAME=
    CLOUDINARY_API_KEY=
    CLOUDINARY_API_SECRET=
    
    # Stripe
    STRIPE_API_KEY=
    ```

2. **Run the application**:

    ```bash
    # Start the server
    cd frontend
    npm run dev

    # Start the client
    cd backend
    npm run dev
    ```

3. **Access the application**:
   Open your browser and go to `http://localhost:5174`.

## About Me

I am Abhishek Sharma a final year student at IIIT Gwalior pursuing Integrated Post Graduate (B.Tech+M.Tech) degree in Information Technology. Do checkout my LinkedIn and connect with me.

### Connect with me :

[![gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abhishek751982@gmail.com)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek-sharma-31b04a213/)


