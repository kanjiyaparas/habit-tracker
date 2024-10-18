# Habit Tracker Backend API

This project provides a backend API for user authentication, habit management, habit tracking, and admin controls, built using Node.js and MongoDB.

## Features

- **JWT-based authentication** for secure user login and registration.
- **CRUD operations** for habits.
- **Scheduled reminders** for pending habits using Cron Jobs.
- **Admin controls** for managing users and creating habit templates.

## Tech Stack

- **Node.js** with **Express.js**
- **MongoDB** with **Mongoose**
- **JWT** for authentication
- **Cron Jobs** for sending reminders

## Setup

### Prerequisites

- [Node.js](https://nodejs.org/) (v14+)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/habit-tracker-backend.git
   cd habit-tracker-backend

## Create a .env file

MONGO_URI=your_mongo_db_uri
JWT_SECRET=your_jwt_secret

