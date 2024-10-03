
# MERN Real Estate Application

## Overview
This is a full-stack real estate web application developed using the MERN stack (MongoDB, Express.js, React.js, Node.js). The platform allows users to explore, search, and filter property listings efficiently based on different criteria. It includes user authentication, responsive design, and a robust admin panel for managing listings.

## Key Features
- **User Authentication**: Users can securely sign up, log in, and log out using JSON Web Tokens (JWT).
- **Property Listings**: Users can view property details, including images, descriptions, prices, and locations.
- **Search & Filter**: Search for properties by location, property type, price range, and more.
- **Responsive Design**: Optimized for desktop, tablet, and mobile views for a seamless experience across devices.
- **Admin Dashboard**: Admins have access to a dedicated dashboard where they can manage property listings (add, update, delete).
- **OAuth Integration**: Support for social login using OAuth providers like Google or Facebook.

## Tech Stack
### Frontend
- **React.js**: Frontend UI framework
- **HTML/CSS/JavaScript**: Standard web technologies for building user interfaces
- **Axios**: For handling HTTP requests

### Backend
- **Node.js & Express.js**: Server-side framework
- **MongoDB**: NoSQL database for storing property and user data
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB and Node.js

### Authentication
- **JWT (JSON Web Tokens)**: For secure user authentication
- **OAuth**: Integration with Google, Facebook, etc., for third-party authentication

### Deployment
- **Render**: Application is hosted and deployed on Render.

## Installation & Setup
To set up and run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. **Install Client Dependencies**:
   ```bash
   cd client
   npm install
   ```

3. **Install Server Dependencies**:
   ```bash
   cd ..
   npm install
   ```

4. **Set Up Environment Variables**:
   Create a `.env` file in the root directory with the following required variables:
   - `MONGO_URI`: MongoDB connection string
   - `JWT_SECRET`: Secret for JWT signing
   - `GOOGLE_CLIENT_ID`: OAuth Google client ID (if using Google sign-in)
   - `GOOGLE_CLIENT_SECRET`: OAuth Google client secret
   - `FACEBOOK_CLIENT_ID`: OAuth Facebook client ID (if using Facebook sign-in)
   - `FACEBOOK_CLIENT_SECRET`: OAuth Facebook client secret

5. **Start the Development Server**:
   ```bash
   npm run dev
   ```

   The application should now be running locally at `http://localhost:3000`.

## Usage
- Visit the [Live Demo](https://evans-mern-real-estate.onrender.com) to explore the app.
- Sign up for a new account or use OAuth (Google/Facebook) to log in.
- Browse, search, and filter property listings.
- Admin users can access the admin panel to add, edit, or delete listings.

## Contributing
We welcome contributions! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes and open a pull request for review.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

This version adds clarity to the instructions and expands on the features/technologies for a better understanding. Let me know if you'd like any further tweaks!#   t e s t  
 