# foodfly
# FoodFly - FastAPI Food Delivery Backend

FoodFly is a robust and scalable backend system for a food delivery application. It features user authentication, restaurant management, food ordering, and admin analytics, all built using **FastAPI** and **MySQL**. The entire application is **Dockerized** for easy deployment.

##  Key Features
* **User Management:** Secure Registration and Login with Role-based access (Admin, Customer, Delivery).
* **JWT Security:** Fully implemented OAuth2 with JSON Web Tokens (JWT) for secure API access.
* **Restaurant & Menu Management:** APIs to manage restaurants and their food items.
* **Order System:** Real-time order placement and tracking logic.
* **Admin Analytics:** Automated report generation (PNG graphs) based on sales and orders.
* **Containerization:** Dockerized environment for consistent performance across systems.

##  Tech Stack
* **Language:** Python 3.9+
* **Web Framework:** FastAPI
* **Database:** MySQL (Structured with SQLAlchemy ORM)
* **Authentication:** OAuth2 & JWT
* **Visualization:** Matplotlib / Seaborn
* **Containerization:** Docker & Docker Desktop

## Project Architecture


The system uses a **Containerized Microservice Architecture** where the FastAPI app communicates with a MySQL database via the `host.docker.internal` bridge.

##  How to Run
1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/foodfly-backend.git](https://github.com/YOUR_USERNAME/foodfly-backend.git)
    ```
2.  **Environment Setup:** Create a `.env` file with your Database credentials.
3.  **Run with Docker:**
    ```bash
    docker-compose up --build
    ```
4.  **Access API Docs:** Open `http://localhost:9000/docs` in your browser.

## 📸 Screenshots
*(Add your screenshots here: Docker Running, Swagger UI, Admin Report Graph)*

## Developed By
**Trinadh**
https://drive.google.com/file/d/1-PnTY1PZHFsJkwRJA-wIVDY6z7XXMpkC/view?usp=drive_link
