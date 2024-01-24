# TravelMate

TravelMate allows users to plan a travel itinerary without having to worry about the details! Travel itineraries are generated using OpenAI where users can select a destination from the explore page as well as enter their own, number of days, interests, and more. Logged in users can save their travel itineraries in their profile and leave reviews.

## Features

### 1. User Authentication

- Secure user authentication system using JWT tokens.
- User registration and login functionality with encrypted password storage.

### 2. AI Generated Travel Itinerary
- Customizable travel itinerary generation using OpenAI API
- Save and edit itinerary for logged in users
- Users can select number of days, interests, transport, etc to generate travel plan according to preferences

### 3. Explore Page
- Users can explore auto-generated travel plans for inspiration

### 4. Review Page
- Reviews of a generated travel plan can be posted for other users to see

### 5. API Integration

- Integration with third-party APIs to enhance functionality and data retrieval.

## Tech Stack
- MERN
    - MondoDB
    - Express
    - React
    - Node

## Run Application

cd application/backend
npm start

In separate shell:

cd application/frontend
npm start
