Realtime Chat Application
Angular • Spring Boot • WebSocket • Docker • Nginx


A full-stack Realtime Chat Application developed using Angular (Frontend) and Spring Boot (Backend) 
with WebSocket-based communication. The application is fully Dockerized for easy setup and deployment.

Key Features:
• Realtime chat using WebSocket (STOMP)
• Angular frontend served via Nginx
• Spring Boot backend with REST APIs
• Dockerized frontend and backend
• Scalable and modular architecture

Project Structure:
- chatapp-frontend (Angular)
- chatapp-backend (Spring Boot)
- Dockerfiles for frontend and backend

Frontend Setup:
1. Install dependencies: npm install
2. Build project: ng build
3. Docker build and run on port 4200

Backend Setup:
1. Build JAR using Maven
2. Docker build and run on port 8080

Docker Commands:
docker build -t chatapp-frontend .
docker run -d -p 4200:80 chatapp-frontend

docker build -t chatapp-backend .
docker run -d -p 8080:8080 chatapp-backend

Access Application:
Frontend: http://localhost:4200
Backend: http://localhost:8080

Interview Summary:
Angular handles UI, Spring Boot manages backend logic, WebSocket enables realtime messaging, 
and Docker ensures consistent deployment.

Author:
Bhushan Madhe

