# Sports Manager

A full-stack web application for managing sports teams, facility reservations and leagues.

Organizing sports activities is often done through messages and spreadsheets, which leads to overlapping bookings, unclear information and mistakes in results. Sports Manager brings everything into one place: teams, court reservations, leagues, match results and automatically updated standings.

The project was developed by an 8-member team over 12 Scrum sprints at the Faculty of Electrical Engineering, University of Sarajevo (2026).

## Features

- **Users and roles** – registration and JWT login with roles (Admin, Captain, Player, Manager), user profiles and password reset
- **Teams** – creating teams, managing rosters and team statistics
- **Reservations** – booking courts and time slots, recurring reservations, approval workflow and conflict prevention
- **Leagues** – creating leagues, adding teams, recording match results and goals
- **Standings** – automatically updated league tables, top scorers and CSV export
- **Calendar and notifications** – calendar view of bookings and matches, in-app notifications
- **Dashboard** – personalized overview depending on the user's role

## Tech stack

- **Frontend:** React 18, Vite
- **Backend:** Java 17, Spring Boot 3, Spring Security, JWT, Spring Data JPA
- **Database:** PostgreSQL 15
- **Testing:** JUnit 5, Mockito, Vitest
- **DevOps:** Docker, Docker Compose, Nginx

## Running the project

Requirements: Docker and Docker Compose.

```bash
git clone https://github.com/tavdovic2/Sports-League-Management-System.git
cd Sports-League-Management-System/projekat
docker compose up -d --build
```

- Frontend: http://localhost:3000
- Backend API: http://localhost:8080

## My role

I worked on league management (adding and removing teams from leagues), the role-based dashboard, captain permissions for managing their own team and reservations, player search in team rosters, and the PostgreSQL database setup.
