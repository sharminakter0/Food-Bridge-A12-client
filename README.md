
# 🍱 FoodBridge – Food Donation Platform

FoodBridge is a full-stack MERN web application designed to reduce food waste by connecting restaurants, individuals, and charitable organizations through an organized food donation system.

Users can browse available food donations, save their favorites, request food items, and confirm pickups through an easy-to-use platform. It helps make surplus food more accessible to people and organizations in need.

---

## 🌐 Live Website

🔗 **Live Demo:** [Visit FoodBridge](https://ass12-foodbridge.web.app/)

## 📸 Project Preview

<p align="center">
  <img
    src="https://i.ibb.co.com/ZR2WvwL4/image.png"
    width="90%"
    alt="FoodBridge Food Donation Platform"
  />
</p>

---

## 🎯 Project Purpose

The main goal of FoodBridge is to minimize food waste and support communities by connecting food donors with people and charitable organizations in need.

The platform encourages restaurants and individuals to donate surplus food while helping users and charities access available donations efficiently.

---

## ✨ Key Features

- 🔐 **User Authentication:** Email/Password and Google authentication using Firebase.
- 👥 **Multiple User Roles:** User, Charity, Restaurant, and Admin.
- 📊 **Role-Based Dashboard:** Separate dashboards and functionality for different user roles.
- 🍱 **Food Donation Management:** Browse and manage available food donations.
- ❤️ **Favorite Donations:** Save favorite food donations for easy access.
- 📩 **Food Request System:** Request available food items.
- 🚚 **Pickup Confirmation:** Confirm food pickups and manage donation status.
- 💳 **Stripe Payment Integration:** Payment integration for charity requests.
- ✅ **Admin Approval Workflow:** Admin approval and management system.
- 🔄 **Status Updates:** Track donation and request statuses.
- ⭐ **Review System:** Users can share feedback and reviews.
- 🔒 **Protected Routes:** Secure private pages and dashboard access.
- 📱 **Responsive Design:** Mobile, tablet, and desktop-friendly interface.

---

## 👥 User Roles

| Role | Responsibilities |
|---|---|
| User | Browse donations, save favorites, request food, and confirm pickups |
| Charity | Access charity-related donation and request features |
| Restaurant | Manage food donations |
| Admin | Manage users, roles, approvals, and platform activities |

---

## 🛠️ Technology Stack

### 🎨 Frontend

- React.js
- React Router DOM
- Tailwind CSS
- Firebase Authentication
- JavaScript

### ⚙️ Backend

- Node.js
- Express.js
- MongoDB
- JWT Authentication

### 💳 Payment Integration

- Stripe

### 🔧 Tools & Services

- Firebase
- Git & GitHub
- npm

---

## 📦 Dependencies

The following are the main libraries and packages used in the project.

### Frontend Dependencies

| Package | Purpose |
|---|---|
| `react` | Building reusable UI components |
| `react-dom` | Rendering React components |
| `react-router-dom` | Managing application routing |
| `firebase` | User authentication |
| `tailwindcss` | Responsive UI styling |
| `@stripe/react-stripe-js` | Integrating Stripe payment elements |
| `@stripe/stripe-js` | Loading Stripe.js in the frontend |

### Backend Dependencies

| Package | Purpose |
|---|---|
| `express` | Building RESTful APIs |
| `mongodb` | Connecting and managing database operations |
| `jsonwebtoken` | Creating and verifying JWT tokens |
| `cors` | Handling cross-origin requests |
| `dotenv` | Managing environment variables |
| `stripe` | Processing payment operations on the server |

**Note:** Check the actual `package.json` files in both repositories and keep only the packages installed and used in your project. Some projects may use different Stripe packages or additional dependencies.

---

## 💡 Why I Used These Technologies

- **React.js:** Used to build reusable components and create an interactive user interface.
- **React Router DOM:** Used to navigate between different pages without reloading the application.
- **Tailwind CSS:** Used to create a clean, consistent, and responsive design.
- **Firebase Authentication:** Used to provide secure Email/Password and Google login functionality.
- **Node.js:** Used as the JavaScript runtime environment for the backend.
- **Express.js:** Used to build backend APIs and handle client-server communication.
- **MongoDB:** Used to store and manage users, food donations, requests, and other application data.
- **JWT:** Used to verify authenticated users when accessing protected backend routes.
- **Stripe:** Used to integrate payment functionality for charity-related requests.

---

## 🔒 Authentication & Security

- Firebase Authentication for user registration and login.
- Email/Password and Google authentication.
- JWT-based authentication for private API routes.
- Role-based access control.
- Protected dashboard functionality.
- Secure payment processing through Stripe.
- Environment variables for sensitive configuration.

---

## 🧩 Challenges Faced During Development

While developing FoodBridge, I worked on several important technical challenges:

- **Multiple User Roles:** Managing different permissions and dashboard functionality for Users, Charities, Restaurants, and Admins.
- **Authentication & Authorization:** Combining Firebase authentication with JWT verification for protected backend APIs.
- **Role-Based Access Control:** Ensuring users can access only the features and resources allowed for their roles.
- **Donation Management:** Managing food donation information and keeping donation statuses updated.
- **Request & Pickup Workflow:** Connecting food requests with donation records and managing pickup confirmations.
- **Payment Integration:** Integrating Stripe to support payment functionality for charity requests.
- **Frontend-Backend Integration:** Connecting React components with Express APIs and MongoDB.
- **Responsive Design:** Creating a consistent experience across different screen sizes.

---

## ✅ Problems Solved Through This Project

FoodBridge addresses several real-world problems through technology:

- **Food Waste Reduction:** Provides a platform where restaurants and individuals can share surplus food instead of wasting it.
- **Food Accessibility:** Helps people and charitable organizations discover available food donations.
- **Donation Coordination:** Organizes the process of browsing, requesting, and managing food donations.
- **Pickup Management:** Makes it easier to confirm pickups and track donation statuses.
- **Accountability:** Provides admin approval and role-based management.
- **Community Support:** Creates a connection between food donors and people who need support.
- **Transparent Feedback:** Allows users to share reviews and feedback about their experience.

---

## ⚙️ Installation & Setup

Follow these steps to run FoodBridge locally.

### 1. Clone the Client Repository

```bash
git clone https://github.com/sharminakter0/FoodBridge-A12.git

cd FoodBridge-A12

npm install
```

### 2. Clone the Server Repository

Open another terminal:

```bash
git clone https://github.com/sharminakter0/FoodBridge-A12-server1.git

cd FoodBridge-A12-server1

npm install
```

### 3. Configure Environment Variables

Create `.env` files in the appropriate client and server directories.

Configure the required credentials for:

**Client:**
- Firebase configuration
- Stripe publishable key

**Server:**
- MongoDB connection string
- JWT secret
- Stripe secret key
- Other required server configuration

Use the exact environment variable names referenced in your source code.

Keep all sensitive credentials private. Never upload `.env` files to GitHub.

### 4. Run the Backend Server

Navigate to the server directory and run the development command configured in its `package.json`.

```bash
npm run dev
```

### 5. Run the Frontend Application

Open another terminal, navigate to the client directory, and run:

```bash
npm run dev
```

The application should now be available at the local URL displayed in your terminal.

**Note:** Check the `scripts` section of each `package.json`. If your project uses a different development command, use that command instead.

---

## 🔗 Project Links

| Resource | Link |
|---|---|
| 🌐 Live Website | [FoodBridge](https://ass12-foodbridge.web.app/) |
| 💻 Client Repository | [GitHub Client](https://github.com/sharminakter0/FoodBridge-A12) |
| ⚙️ Server Repository | [GitHub Server](https://github.com/sharminakter0/FoodBridge-A12-server1) |
| 👩‍💻 Developer GitHub | [sharminakter0](https://github.com/sharminakter0) |
| 💼 LinkedIn | [Connect with me](https://www.linkedin.com/in/sharmin-akter0s/) |
| 🌐 Portfolio | [Visit My Portfolio](https://sharminaktercode.netlify.app/) |

---

## 🚀 Future Improvements

- Real-time notification system.
- Improved donation tracking.
- Advanced search and filtering.
- Admin analytics dashboard.
- Improved UI/UX.
- More detailed donation and request reports.

---

## 👩‍💻 Developer

**Sharmin Akter**

Full-Stack Web Developer

- GitHub: [sharminakter0](https://github.com/sharminakter0)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/sharmin-akter0s/)
- Portfolio: [Visit My Portfolio](https://sharminaktercode.netlify.app/)

---

<p align="center">
  💚 Together, Let's Reduce Food Waste and Make a Difference!
</p>

<p align="center">
  ⭐ Thank you for visiting this project!
</p>
