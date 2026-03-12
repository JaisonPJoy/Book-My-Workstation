# Book My Workstation – Workplace Reservation System

## Overview

**Book My Workstation** is a full-stack web application developed using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.
The system allows employees to **reserve office workstations, meeting rooms, and conference halls** when returning to office after remote work during the COVID-19 period.

The platform helps organizations manage workspace usage while ensuring **social distancing and efficient resource allocation**.

---

## Problem Statement

After the COVID-19 pandemic, many companies adopted **hybrid work models**, where employees returned to office on selected days.

Managing office seating manually created problems such as:

* overcrowded workspaces
* lack of visibility of available desks
* difficulty booking meeting rooms
* challenges maintaining social distancing

This system solves those problems by providing a **digital workspace reservation platform**.

---

## Features

### User Authentication

* Secure login and authentication system for employees.

### Office Location Selection

* Employees can choose their **office location or branch** before booking.

### Workspace Booking

* Users can reserve **available workstations** for specific days.

### Meeting Room Reservation

* Employees can book **meeting rooms and conference halls**.

### Reservation Visibility

* The system displays **already reserved desks**, allowing employees to maintain **social distancing** by selecting distant seats.

### Real-Time Availability

* Shows available and reserved workspaces dynamically.

---

## Technologies Used

### Frontend

* React.js
* HTML
* CSS
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Architecture

The system follows the **MERN stack architecture**:

* **React** – User interface and booking dashboard
* **Node.js & Express.js** – API and server logic
* **MongoDB** – Data storage for users, workspaces, and bookings

---

## Key Modules

### Authentication Module

* User login and session management.

### Office Management Module

* Select office location or branch.

### Workspace Booking Module

* Book desks based on availability.

### Meeting Room Booking Module

* Reserve meeting rooms and conference halls.

### Reservation Tracking

* Displays currently reserved workspaces.

---

## Installation

### 1. Clone the repository

```bash id="7c3qaa"}
[git clone https://github.com/yourusername/book-my-workstation.git](https://github.com/JaisonPJoy/Book-My-Workstation.git)
```

### 2. Navigate to the project folder

```bash id="1ekyio"}
cd book-my-workstation
```

### 3. Install dependencies

```bash id="e3g5v1"}
npm install
```

### 4. Start the backend server

```bash id="jrf63p"}
npm start
```

### 5. Start the React frontend

```bash id="kvev8x"}
npm start
```

---

## Future Improvements

* Add calendar-based booking interface
* Implement real-time seat map visualization
* Enable admin dashboard for workspace management
* Add email notifications for booking confirmations

---

## Author

Jaison P Joy
