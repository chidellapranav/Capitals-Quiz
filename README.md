# Country Capitals Quiz Website

This repository hosts a web application for a quiz on country capitals. The app is built using Node.js and utilizes PostgreSQL for data storage. The frontend is developed with `.ejs` for templating and `.css` for styling.

---

## Features
- Interactive quiz to test knowledge of country capitals.
- Fetches data dynamically from a PostgreSQL database.
- Responsive design for an engaging user experience.
- Seamless integration of backend and frontend using `.ejs` templates.

---

## Tech Stack
- **Backend**: Node.js
- **Database**: PostgreSQL
- **Templating Engine**: Embedded JavaScript (.ejs)
- **Styling**: CSS

---

## Installation

### Prerequisites
- Node.js and npm installed.
- PostgreSQL installed and running.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url
   cd country-capitals-quiz
2. Install dependencies L
   ```bash
   npm install
3. Configure the database:

    a.)Create a PostgreSQL database.
    b.)Populate it with the provided SQL schema and seed data.
    c.)Update the config object in **db.js** with your database credentials.
4. Start the application:
   ```bash
   npm start
5. Access the website at **_http://localhost:3000_**.
   
---
### Folder Structure:
a.) /public - Contains static files like CSS and JavaScript.
b.) /views - .ejs templates for rendering pages.
c.) /routes - Backend routes for handling HTTP requests.
d.) /db.js - Database connection and queries.
e.) /app.js - Main server file.

---
### Usage:

1.) Open the homepage and start the quiz.
2.) Answer the questions displayed on the screen.
3.) The app will evaluate and display the results.

---
### Database Schema:

Table: questions

    id (Primary Key): Unique identifier for each question.
    country: Name of the country.
    capital: Capital of the country.
  ---
### License:
This project is licensed under the MIT License. See the LICENSE file for details.

   
 
