# 📘 Bookstore API with Flask & MySQL (Docker Compose)

### 📋 Project Overview
This is a simple **Flask-based Bookstore API** application that connects to a **MySQL** database. It is containerized using **Docker** and managed with **Docker Compose**. The project demonstrates how to:
- Package a Flask app with dependencies
- Connect it to a MySQL database container
- Use `docker-compose` to orchestrate services

---

### 🛠 Technologies Used
- Python + Flask
- MySQL 5.7
- Docker & Docker Compose

---

### 📂 Project Structure

```
├── bookstore-api.py # Flask app with MySQL connection and RESTful endpoints
├── Dockerfile # Image build config for the Flask app
├── docker-compose.yml # Orchestration for app and MySQL services
├── requirements.txt # Python dependencies



```

### 🚀 How to Run the Project

1. **Clone the repo**  

   ```bash
   git clone <this-repo-url>
   cd <project-folder>
   ```
2 Start services with Docker Compose

	docker compose up --build
	
3- Access the API
	
	The Flask app will be available at:
	
	👉 http://localhost/books

Example Endpoints

GET / → Welcome message

GET /books → List all books

GET /books/<id> → Get a book by ID

POST /books → Add a new book

PUT /books/<id> → Update book

DELETE /books/<id> → Delete book
  
