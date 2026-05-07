# Flask + MySQL Two-Tier Application

This project is a simple two-tier application built using Flask and MySQL with Docker Compose. The purpose of this project is to understand how multiple containers communicate with each other, how Docker networking works, and how persistent storage is managed using Docker volumes.

The application consists of:
- A Flask backend container
- A MySQL database container

Both containers are connected using a user-defined bridge network created through Docker Compose.

## Technologies Used

- Python
- Flask
- MySQL
- Docker
- Docker Compose

## Project Structure

```bash
flask-sql/
│
├── docker-compose.yml
├── Dockerfile
├── app.py
├── requirements.txt
└── README.md
