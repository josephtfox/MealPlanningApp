# Meal Planning Web Application Project

## Project Overview
The Meal Planning Web Application is a full-stack web application that allows users to plan their meals for the week, select recipes, and generate a weekly grocery list.

## Tech Stack
- Backend: Flask (Python)
- Frontend: React (JavaScript)
- Database: MongoDB (MongoDB Atlas for production)
- Additional Libraries: Flask-RESTful, Axios

## Project Structure

### Backend (Flask)
1. **`app.py` (Main Flask Application):**
    - Defines the main Flask application.
    - Configures MongoDB connection using Flask-PyMongo.
    - Includes sample API endpoint (`'/api/hello'`).

2. **`models.py` (MongoDB Models):**
    - Defines MongoDB models for meals and ingredients.
    - Uses Flask-PyMongo to interact with the database.

3. **API Endpoints:**
    - `/api/hello`: Sample endpoint.
    - `/api/meals`: CRUD operations for meals.
    - `/api/ingredients`: CRUD operations for ingredients.

### Frontend (React)
1. **React App (Created with Create React App):**
    - Created using `npx create-react-app meal-planning-app`.
    - Additional dependencies installed: Axios, React Router.

2. **React Components:**
    - `Home.js`: Home page component.
    - `Meals.js`: Component for displaying and managing meals.
    - `Ingredients.js`: Component for displaying and managing ingredients.
    - Add additional components as needed.

3. **Routing:**
    - Configured with React Router.
    - Routes for home, meals, and ingredients.

## Project Setup

### Backend
1. Install Flask and Flask-RESTful:
