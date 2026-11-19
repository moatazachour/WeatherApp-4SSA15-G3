# MeteoProject - Weather Application Microservices

## Description

A weather application based on a microservices architecture, allowing users to check real-time weather conditions, manage favorite cities, and receive personalized weather alerts.

## Team (Class 4SSA15-G3)

- Moataz Achour
- Nadim Sboui
- Chrif Smaya
- Adel Ben Sassi
- Omar Bousrih

## Overall Architecture

The project is divided into 6 microservices:

1. **Access Service (Auth + Gateway):** User management, JWT authentication, and routing. (PostgreSQL)
2. **Location Service:** Countries, regions, and cities. (PostgreSQL)
3. **Weather Service:** Weather data, forecasts, and OpenWeatherMap API integration. (MongoDB)
4. **Alert Service:** Threshold management and alert triggering. (PostgreSQL)
5. **Preferences Service:** Favorite cities and user settings. (MongoDB)
6. **Notification Service:** Sending emails, SMS, and push notifications. (MongoDB)

## Technologies Used

- **Backend:** Spring Boot (Java) / ASP.NET Core (C#) for Notifications
- **Frontend:** Angular
- **Infrastructure:** API Gateway, Eureka, Config Server, Keycloak, Docker
- **Databases:** PostgreSQL, MongoDB
- **Communication:** OpenFeign (Synchronous), RabbitMQ (Asynchronous)

## Repository Structure

- `Backend/`: Contains the projects for each microservice.
- `Frontend/`: Client application.
- `Documentation/`: Presentations, diagrams, and technical documentation.
- `README.md`: This file.

## How to Run the Project

_(To be completed during the development phase)_
