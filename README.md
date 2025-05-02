# ⚡ EV E-Commerce Website

A full-stack Electric Vehicle (EV) E-commerce Website where users can
explore various EV models, compare features, and pre-book vehicles with
integrated Razorpay payments.\
Built with React (frontend) and Node.js/Express (backend), with a
modern, yellow-themed UI design.

## 🛠️ Tech Stack

\- Frontend: React.js, Tailwind CSS\
- Backend: Node.js, Express.js\
- Payment Gateway: Razorpay\
- Database: (Optional: MongoDB/MySQL)\
- Email Service: Nodemailer\
- Deployment: (Optional: Vercel, Render, or custom hosting)

## 🚗 Features

-   🌟 Homepage with dynamic word effects (Elegance, Minimalism,
    Comfort).

-   🌟 Image carousel showcasing EV models.

-   🌟 Product Comparison to help users compare different EV models
    side-by-side.

-   🌟 Product Details Pages for SE03 Lite, SE03, SE03 Max models.

-   🌟 Pre-booking System with Razorpay payment integration.

-   🌟 Email Confirmation after successful booking.

-   🌟 Responsive Design for mobile and desktop.

-   🌟 Themed UI with dark greys, black, white, and vibrant yellow
    (#F9ED32, #FFF225).

## 🚀 How to Run Locally

1\. Clone the repository

git clone https://github.com/DonAshley187/EV-E-commerce-Website.git
cd EV-E-commerce-Website

2\. Start backend server:

cd BTS\
node server.js

3\. Setup Frontend:

cd frontend\
npm install\
npm start

The frontend will run on http://localhost:3000

The backend will run on http://localhost:5000

## 💳 Razorpay Payment Flow

1\. User selects a model to pre-book.\
2. Fills out the PreBook form (product name auto-filled).\
3. Razorpay payment gateway popup appears.\
4. After successful payment:\
- Razorpay sends payment info to backend.\
- Backend sends email receipt confirmation to the user.

## 📬 Email Receipt

\- Nodemailer is used to send a booking confirmation email containing:\
- Customer name\
- Vehicle booked\
- Booking ID\
- Payment details

## ✨ Future Enhancements (optional ideas)

-   🚀 Add User Authentication (JWT tokens).

-   🚀 Order Tracking dashboard.

-   🚀 Admin panel to manage bookings.

-   🚀 Full Database Integration (MongoDB/MySQL) for pre-book data
    persistence.

-   🚀 Reviews & Ratings for EV models.

## 👩‍💻 Author

Ashwin Shinde



