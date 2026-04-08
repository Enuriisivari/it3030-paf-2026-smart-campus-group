# Smart Campus Operations Hub

A modern web platform for university operations, managing facility/asset bookings and maintenance incidents.

## Business Scenario
A university is modernizing its day-to-day operations. This platform serves as a single portal for:
- **Facility and Asset Bookings:** Managing reservations for rooms, labs, and equipment.
- **Maintenance and Incident Handling:** Tracking fault reports, technician updates, and resolutions.
- **Role-Based Access:** Ensuring secure and auditable workflows for staff, students, and technicians.

## System Architecture
The application uses a modern decoupled architecture:
- **Backend:** A Java 17, Spring Boot 3 REST API emphasizing RESTful best practices (layered architecture, validation, error handling, security). It connects to a MongoDB database.
- **Frontend:** A React client application built with Vite. It provides an intuitive, dynamic user interface with responsive vanilla CSS styling, tailored to modern web design standards.

## Project Structure
- `/backend` - Spring Boot (Java) project. Includes layers for `controller`, `service`, `repository`, `model`, `dto`, `exception`, `security`, and `config`.
- `/frontend` - React / Vite project. Includes folders for `components`, `pages`, `services`, `utils`, `context`, and `styles`.

## Quick Start Requirements
- **Java** 17
- **Node.js** 24+ & **npm**
- **MongoDB** (Local or Atlas)

### Running the Backend
1. Open a terminal and navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Build and run the project:
   ```bash
   ./mvnw spring-boot:run
   ```
   The backend will start on port 8080.

### Running the Frontend
1. Open another terminal and navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies (if not already done) and start the development server:
   ```bash
   npm install
   npm run dev
   ```
   The Vite React app will be accessible at http://localhost:5173.