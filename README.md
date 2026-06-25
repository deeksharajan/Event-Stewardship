#  Event Stewardship

## Overview

Event Stewardship is a responsive event management web application developed using **React.js** by a team of three students. The application provides a centralized platform for managing event registrations, event scheduling, catering preferences, accommodation requirements, and booking reviews through an intuitive and user-friendly interface.

This project was developed as part of our **First Year – Second Semester coursework** to explore modern web development concepts such as component-based architecture, client-side routing, state management, form validation, and responsive user interface design.

---

##  Features

###  User Management

* User Registration
* User Login
* Personal Details Management

###  Event Management

* Event Selection and Booking
* Event Scheduling
* Date and Time Selection
* Venue Management

###  Catering Services

* Vegetarian & Non-Vegetarian Options
* Snacks Selection
* Vendor-Based Catering Preferences

###  Accommodation Services

* Accommodation Requirement Selection
* Room Type Selection
* Stay Planning Options
###  Booking Management

* Save Event Details
* View Booking Information
* Form Validation for Required Fields

###  User Experience

* Responsive Design for All Devices
* Multi-page Navigation using React Router
* Interactive and User-Friendly Interface

---

##  Technologies Used

### Frontend

* React.js
* React Router DOM
* JavaScript (ES6+)
* HTML5
* CSS3

### Backend

* Node.js
* Express.js
* REST API Architecture

### Database

* MongoDB
* Mongoose

---

## Backend Architecture
The backend of the application is built using Node.js and Express.js, which handles all server-side operations and API requests.

### Backend Responsibilities
* Handles user registration and login requests
* Manages event booking data
* Stores and retrieves user information
* Validates incoming form data
* Connects frontend with database
* Provides RESTful API endpoints

---

## API Workflow
- Frontend (React) sends request to backend
- Express server receives the request
- Data is validated and processed
- Information is stored in MongoDB
- Response is sent back to frontend

---

## Database Structure

The system uses **MongoDB** collections to store:

- Users
- Events
- Bookings
- Catering preferences
- Accommodation details

Each collection is structured using **Mongoose schemas** for consistency and validation.

---


##  Project Structure

```text
src/
│
├── App.jsx
├── Details.jsx
├── Event.jsx
├── Exit.jsx
├── Login.jsx
├── Personal.jsx
├── Register.jsx
├── Server.js
├── View.jsx
├── index.css
└── main.jsx

```

---

##  Workflow

* Register or Login to the application.
* Enter personal details.
* Select an event category.
* Provide event information such as date, time, and venue.
* Choose catering preferences.
* Select accommodation requirements.
* Save event details.
* Review submitted booking information.

---

##  Learning Outcomes

Through this project, we gained practical experience in:

* React Functional Components
* React Hooks (`useState`)
* React Router Navigation
* Form Handling and Validation
* State Management
* Responsive Web Design
* Full-stack application development
* API development using Express.js
* Team Collaboration using Git and GitHub

---

##  Future Enhancements

* JWT-based authentication system
* Online payment gateway integration
* Admin dashboard for event control
* Vendor management system
* Email notifications
* Event analytics & reporting
* Booking history tracking
* Deployment on cloud platforms

  
---


##  Project Goal

The goal of Event Stewardship is to simplify event planning and booking through a user-friendly platform while helping students gain practical experience in modern full-stack web development using React.js, Node.js, and MongoDB


