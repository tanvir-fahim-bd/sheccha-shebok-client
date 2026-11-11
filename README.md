# Sheccha Shebok – Volunteer & Social Welfare Platform

**Sheccha Shebok** is a volunteer management and social welfare platform designed to connect people with volunteering opportunities and charitable events. It allows users to discover events, contribute donations, register as volunteers, and manage their activities through personalized dashboards.

The platform also provides an administrative dashboard where administrators can manage events, volunteers, notices, and user roles.

## 🌐 Live Project

- **Live Website:** https://humanity-hand.web.app/
- **Live API:** https://sheccha-shebok-server.vercel.app/
- **Server Repository:** https://github.com/TanvirFahimBD/sheccha-shebok-server

---

## 📸 Project Screenshots

<!-- Add actual project screenshots to the screenshots directory -->

| Home Page | Dashboard |
|:---:|:---:|
| ![Home Page](./screenshots/home.png) | ![Dashboard](./screenshots/dashboard.png) |

| Events | Event Details |
|:---:|:---:|
| ![Events](./screenshots/events.png) | ![Event Details](./screenshots/event-details.png) |

---

## ✨ Key Features

### 👤 User Features
- Browse and search available volunteering events.
- Donate to support social welfare activities.
- Access a personalized dashboard.
- View and update personal profile information.

### 🤝 Volunteer Features
- Browse and search volunteering opportunities.
- Register for available events.
- View personal event registrations.
- Receive important event notices.
- Add and view personal reviews.
- Update personal profile information.

### 🛡️ Admin Features
- Create and publish new events.
- Update and delete existing events.
- Create and manage event notices.
- Assign volunteer roles.
- Remove volunteers.
- Assign new administrator roles.
- Update personal profile information.

### 🔒 Additional Features
- Firebase Authentication.
- Role-based dashboard access.
- Protected routes for authenticated users.
- Custom 404 page for invalid routes.
- Continuous feature improvements.

---

## 🛠️ Technologies Used

### Frontend
- **React.js** – Building reusable UI components and interactive user interfaces.
- **React Router** – Managing client-side routing and navigation.
- **Firebase Authentication** – Handling user authentication and account management.

### Backend
- **Node.js** – Providing the server-side JavaScript runtime.
- **Express.js** – Building RESTful APIs and managing backend routes.
- **MongoDB** – Storing and managing application data.

### Deployment & Hosting
- **Firebase Hosting** – Hosting the frontend application.
- **Vercel** – Deploying and hosting the backend API.
- **Railway** – Used during development/deployment (confirm its exact role in this version).

---

## 📦 Dependencies

### Frontend Dependencies

The following are the main expected dependencies based on the project architecture:

- react
- react-dom
- react-router-dom
- firebase

### Backend Dependencies

- express
- mongodb
- cors
- dotenv

> **Note:** Verify the exact dependencies and versions from your frontend and backend `package.json` files before publishing this section.

---

## ⚙️ Run Locally

Follow these steps to run the project on your local machine.

### Prerequisites

Make sure you have installed:

- Node.js (LTS recommended)
- npm
- Git
- MongoDB account or local MongoDB server
- Firebase project with Authentication configured

### 1. Clone the Backend Repository

```bash
git clone https://github.com/TanvirFahimBD/sheccha-shebok-server.git

cd sheccha-shebok-server
```

### 2. Install Backend Dependencies

```bash
npm install
```

### 3. Configure Backend Environment Variables

Create a `.env` file in the backend root directory.

```env
PORT=5000
DB_USER=your_mongodb_username
DB_PASS=your_mongodb_password
```

Add other environment variables required by your backend implementation.

### 4. Start the Backend Server

```bash
npm start
```

If your project uses a development script, you can use:

```bash
npm run dev
```

Backend API:

```text
http://localhost:5000
```

### 5. Set Up the Frontend

Clone the client repository (add your actual client repository URL here).

```bash
git clone YOUR_CLIENT_REPOSITORY_URL

cd YOUR_CLIENT_DIRECTORY
```

Install dependencies:

```bash
npm install
```

### 6. Configure Frontend Environment Variables

Create a `.env` file in the frontend root directory.

```env
REACT_APP_API_URL=http://localhost:5000

REACT_APP_apiKey=your_firebase_api_key
REACT_APP_authDomain=your_firebase_auth_domain
REACT_APP_projectId=your_firebase_project_id
REACT_APP_storageBucket=your_firebase_storage_bucket
REACT_APP_messagingSenderId=your_firebase_sender_id
REACT_APP_appId=your_firebase_app_id
```

> Adjust the environment variable names and frontend API configuration according to the actual project setup. For a Vite project, use the `VITE_` prefix instead of `REACT_APP_`.

### 7. Start the Frontend

```bash
npm start
```

For Vite-based projects:

```bash
npm run dev
```

The application should now be accessible through your local development server.

---

## 🧠 Technology Choices & Why I Used Them

| Technology | Purpose |
|---|---|
| React.js | Building a component-based and reusable frontend |
| React Router | Managing navigation and protected routes |
| Firebase Authentication | Providing user authentication |
| Node.js | Running server-side JavaScript |
| Express.js | Developing REST APIs and backend services |
| MongoDB | Managing users, events, registrations, and other application data |
| Firebase Hosting | Deploying the frontend application |
| Vercel | Hosting the backend API |

---

## 🚧 Challenges Faced During Development

Some important engineering challenges addressed while building the platform:

- **Role-Based Access Control:** Managing different permissions and dashboard experiences for users, volunteers, and administrators.
- **Authentication & Authorization:** Integrating Firebase Authentication with protected routes and role-based access.
- **Event Management:** Implementing complete event management workflows, including creation, updating, deletion, and volunteer registration.
- **Data Management:** Managing multiple types of application data, including user profiles, events, registrations, reviews, donations, and notices.
- **Frontend & Backend Integration:** Connecting React components with Express APIs and handling asynchronous data communication.
- **Deployment Configuration:** Connecting the Firebase-hosted frontend with the Vercel-hosted backend API.

---

## 💡 Problems Solved

- Simplified the process of discovering volunteering opportunities.
- Created a centralized platform for volunteer event registration.
- Provided administrators with tools to manage events and volunteers.
- Enabled users to manage their profiles and volunteering activities.
- Improved communication through event notices.
- Provided a review system for volunteers to share their experiences.
- Established separate role-based dashboards for different types of users.

---

## 🔮 Future Improvements

- Online payment gateway integration for donations.
- Advanced event filtering and searching.
- Email and real-time notifications.
- Admin analytics and reporting dashboard.
- Improved volunteer engagement and management.
- Additional security and performance optimizations.

---

## 👨‍💻 Developer

**Tanvir Hossain Fahim**  
Software Engineer | Full-Stack Developer

- **Portfolio:** https://tanvir-fahim-bd.netlify.app/
- **GitHub:** https://github.com/TanvirFahimBD
- **LinkedIn:** https://www.linkedin.com/in/tanvir-fahim/

---

⭐ If you find this project interesting, consider giving it a star!

**Built with ❤️ to encourage volunteering and social welfare.**
