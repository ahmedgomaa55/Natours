<h1 align="center">
  <br>
  <a href="https://natours-api-z82r.onrender.com/"><img src="https://github.com/lgope/Natours/blob/master/public/img/logo-green-round.png" alt="Natours" width="200"></a>
  <br>
  Natours App
  <br>
</h1>
  
## Natours App 

Welcome to Natours! This web application is made for people who love travelling and going on tour vacations.



## Technologies 

- Node.js
- Express.js
- MongoDB
- Mongoose
- HTML, CSS
- Pug (Template Engine)
- Mailtrap
- Mapbox
- Stripe
- JSON Web Token
- bcrypt
- Nodemailer
- Gmail
  
## Features 

- [x] Browse and book a variety of nature tours.
- [x] Signup and create your own account!
- [x] Login to your account!
- [x] Each login session is persisted using cookies
- [x] Detailed information about each tour, including duration, difficulty, and price.
- [x] Interactive maps to visualize tour destinations.
- [x] Tour reviews and ratings by fellow travelers.
- [x] Reset your password
- [x] Update your password and profile
- [x] Stripe payment checkout gateway 
- [x] Upload Profile Picture
- [x] Email service 
- [x] Responsive for different platforms

## Setting Up Your Local Environment

Follow these steps to set up your local environment for the Natours app:

1. **Clone the Repository:**
   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/alin00r/natours.git
   cd natours
   ```
2. **Install Dependencies:**
   Run the following command to install all the required dependencies:
   ```bash
   npm install
   ```
3. **Configure Environment Variables:**

   Before you can run the Natours app, you need to set up your environment variables. Follow these steps to configure your environment variables:

   1. **Create a `.env` File:**
      In the root directory of the app, create a file named `.env`.

   2. **Add the Following Environment Variables:**
      Replace the placeholders with your actual information. You might need to sign up for accounts and services to obtain the required credentials.

      ```dotenv

      # MongoDB Configuration
      DATABASE=your-mongodb-database-url
      USERNAME=your-mongodb-username
      DATABASE_PASSWORD=your-mongodb-password

      # JSON Web Token Configuration
      SECRET=your-json-web-token-secret
      JWT_EXPIRES_IN=90d
      JWT_COOKIE_EXPIRES_IN=90

      # Stripe Configuration
      STRIPE_SECRET_KEY=your-stripe-secret-key
      STRIPE_WEBHOOK_SECRET=your-stripe-webhook-secret

      ```

# API reference

During API development, I use `Postman` for testing API.

- Postman documentation is available on this link [Natours API Documentation](https://documenter.getpostman.com/view/32375212/2sA2r3YQxj)
- Base URL endpoints: `http://127.0.0.1:3000/api/V1/` or `http://localhost:3000/api/v1/`

## Project Demo 

#### Home Page :
https://github.com/gomaa55/Natours/assets/81438589/477e24ef-7027-4dbb-a0c8-049ab9d3a750

#### Tour Details :
https://github.com/gomaa55/Natours/assets/81438589/a29aae95-96f4-413e-8a5d-5fe42bac72e9

#### Payment Process :
https://github.com/gomaa55/Natours/assets/81438589/a6b0fdb5-6a9e-4713-8735-c826705d15af

#### Booked Tours :
https://github.com/gomaa55/Natours/assets/81438589/866447f5-1b94-4387-8870-63f9e4791e08

#### User Profile :
https://github.com/gomaa55/Natours/assets/81438589/1082ee57-3ccf-4d22-a96d-d6dd49cae68b



## License

[![License](https://img.shields.io/:License-MIT-blue.svg?style=flat-square)](http://badges.mit-license.org)
