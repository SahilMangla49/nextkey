# Real Estate Website

## Overview

The Real Estate Website is a web application designed to showcase property listings and handle user authentication. It features a responsive design and allows users to view, register, and log in to manage their profiles and view property recommendations.

## Tech Stack

- **Frontend**: React (with Vite), Tailwind CSS
- **Backend**: Node.js (with Express.js)
- **Database**: MongoDB
- **Deployment**: Heroku (for backend and AI API), Vercel or Netlify (for frontend)

## Features

1. **User Authentication**: 
   - Login and registration flows with JWT for session management.
   - Protected profile page to view and manage user information.
   
2. **Property Listing Page**:
   - Displays a list of properties with details and images.
   
3. **AI-Driven Property Recommendation**:
   - Provides property recommendations based on user preferences and browsing history.

## Setup Instructions

### Prerequisites

- Node.js and npm (or yarn)
- Python (for AI algorithm)
- MongoDB (local or cloud instance)

### Frontend Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/real-estate-website.git
   cd real-estate-website/frontend
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Start the Development Server**

   ```bash
   npm run dev
   ```

   The frontend will be available at `http://localhost:3000`.

### Backend Setup

1. **Navigate to Backend Directory**

   ```bash
   cd nextkey-website/backend
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Configure Environment Variables**

   Create a `.env` file and add the following variables:

   ```
   MONGODB_URI=your-mongodb-uri
   JWT_SECRET=your-jwt-secret
   ```

4. **Start the Server**

   ```bash
   npm start
   ```

   The backend will be available at `http://localhost:5000`.

## Deployment

### Frontend Deployment

- **Vercel** or **Netlify** can be used for deploying the React frontend.
- Ensure to update environment variables and build settings as needed.


## Contributing

Feel free to open issues or submit pull requests. Contributions are welcome!


## Contact

For any questions or feedback, please reach out to [your-email@example.com](mailto:your-email@example.com).