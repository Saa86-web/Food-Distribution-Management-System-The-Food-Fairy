# Food-Distribution-Management-System-The-Food-Fairy
# Food Distribution Management System: The Food Fairy

## Overview

The Food Fairy is a web application designed to facilitate food distribution in communities, connecting food donors with beneficiaries and managing the logistics of food donation and delivery.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication with JWT
- Different user roles (donors, beneficiaries, admins)
- Food donation management
- Delivery tracking
- Validations and error handling

## Technologies Used

- **Back-End**: Node.js, Express.js, MongoDB
- **Front-End**: React
- **Authentication**: JSON Web Tokens (JWT), bcrypt
- **Validation**: Joi

## Installation

### Prerequisites

1. **Node.js and npm**: Ensure you have [Node.js](https://nodejs.org/) installed.
2. **MongoDB**: Set up a local MongoDB server or create a MongoDB Atlas account.

### Clone the Repository

```bash
git clone https://github.com/yourusername/food-fairy.git
cd food-fairy
Back-End Setup
Navigate to the back-end directory:

bash
Copy code
cd backend
Install dependencies:

bash
Copy code
npm install
Create a .env file in the root of the back-end directory and add the following:

plaintext
Copy code
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Replace your_mongodb_connection_string and your_jwt_secret with your actual MongoDB URI and a secure random string.

Front-End Setup
Navigate to the client directory:

bash
Copy code
cd client
Install dependencies:

bash
Copy code
npm install
Running the Application
Start the Back-End Server
Navigate back to the back-end directory:

bash
Copy code
cd backend
Start the server:

bash
Copy code
node server.js
Start the Front-End Application
Open another terminal window and navigate to the client directory:

bash
Copy code
cd client
Start the React application:

bash
Copy code
npm start
Access the Application
Open your web browser and go to http://localhost:3000 for the front-end.
The back-end API will be available at http://localhost:5000/api.
Usage
Register a New User: Navigate to the registration page and fill out the form.
Log In: Use your credentials to log in and access the application features.
Manage Food Donations: Donors can submit food items, and beneficiaries can request food.
API Endpoints
Authentication
POST /api/auth/register: Register a new user.
POST /api/auth/login: Log in and receive a JWT.
Donors
GET /api/donors: Retrieve all donors.
POST /api/donors: Create a new donor.
Beneficiaries
GET /api/beneficiaries: Retrieve all beneficiaries.
POST /api/beneficiaries: Create a new beneficiary.
Distribution Centers
GET /api/distribution-centers: Retrieve all distribution centers.
POST /api/distribution-centers: Create a new distribution center.
Food Types
GET /api/food-types: Retrieve all food types.
POST /api/food-types: Create a new food type.
Delivery Records
GET /api/deliveries: Retrieve all delivery records.
POST /api/deliveries: Create a new delivery record.
Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License - see the LICENSE file for details.

vbnet
Copy code



This `README.md` provides clear instructions for setting up, running, and using the Food Distribution Management System. If you need more information or additional sections, let me know!


