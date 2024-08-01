# LeaderApp

## Overview

The LeaderApp is a real-time application developed with Spring Boot that manages and displays player scores. Users can submit scores at any time, and the application will dynamically update and show the top 5 players based on their scores. Real-time updates are handled via APIs, and Postman is used for API testing.

## Features

- **User Data Input**: Allows users to submit their scores at any time.
- **Real-Time Updates**: The leaderboard updates in real-time with new scores and rankings.
- **Top 5 Display**: Always displays the top 5 players based on their scores.
- **API Integration**: Utilizes RESTful APIs for score submission and leaderboard retrieval.

## Technologies Used

- **Backend**: Spring Boot (Java)
- **Database**: H2 Database (for simplicity; can be replaced with MySQL/PostgreSQL in production)
- **API Testing**: Postman
- **Real-Time Updates**: Spring WebSocket (for real-time functionality)

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 11 or later
- Apache Maven (for building the project)
- Postman (for testing APIs)

