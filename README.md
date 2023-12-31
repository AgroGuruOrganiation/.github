# AgroGuru - Empowering Farmers with Crop Prediction and Agricultural Information

AgroGuru is a comprehensive web application developed using the MERN (MongoDB, Express, React, Node.js) stack. It aims to assist farmers by providing accurate crop predictions through Machine Learning, delivering real-time weather information, offering resources such as nearby laboratories, markets, and nurseries, all while incorporating JWT authentication for secure user access.

## Features

- **Crop Prediction:** Utilizes Machine Learning algorithms to predict optimal crops based on various factors.
- **Weather Information:** Real-time weather updates and forecasts for better agricultural planning.
- **User Roles:** Supports different user roles - farmer, crop seller, with tailored features.
- **Location-based Information:** Provides details about nearby laboratories, markets, and nurseries.
- **JWT Authentication:** Implements secure user access using JSON Web Tokens.
- **Database Integration:** Stores user data, predictions, and other essential information using MongoDB.

## Tech Stack

- **Frontend:** React.js with JavaScript for interactive user interfaces.
- **Backend:** Node.js and Express.js for server-side logic and APIs.
- **Database:** MongoDB for efficient data storage and retrieval.
- **Authentication:** JWT (JSON Web Tokens) for secure user authentication.
- **Machine Learning:** ML algorithms for crop prediction.
- **Weather Data:** Integration with weather APIs for real-time weather information.

## Getting Started

1. Clone the repository: `git clone https://github.com/yourusername/AgroGuru.git`
2. Navigate to the project directory: `cd AgroGuru`
3. Install dependencies for both frontend and backend: `npm install`
4. Configure MongoDB connection: Update the database configuration in `server/config/config.js`.
5. Set up JWT secret: Update the secret key in `server/config/config.js` for authentication.
6. Start the backend server: `npm run server`
7. Start the frontend development server: `npm run client`
8. Access the application in your web browser at `http://localhost:3000`

## Usage

- Farmers and sellers can register and log in with appropriate roles.
- JWT authentication ensures secure user access to the application.
- Farmers can input various parameters to get crop predictions.
- Real-time weather updates are displayed on the dashboard.
- Users can explore nearby laboratories, markets, and nurseries.
- All data is stored in the MongoDB database for easy retrieval.


---

AgroGuru empowers farmers with crop prediction using Machine Learning, real-time weather information, and essential agricultural resources, built with the MERN stack and incorporating JWT authentication. 
