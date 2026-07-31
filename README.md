# 📝 Full-Stack Blog Web App & REST API

A full-stack blog management application built with **Node.js** and **Express.js**. The project separates backend data management and frontend rendering into two distinct services communicating via HTTP requests.

---

## 🏗️ Architecture Overview

* **REST API Server (`index.js` / Port 4000):** Acts as the backend service. It manages in-memory blog posts and exposes RESTful endpoints for CRUD operations.
* **Frontend Web Client (`server.js` / Port 3000):** Serves the user interface using **EJS** templates and uses **Axios** to send HTTP requests to the REST API server.

---

## 🛠️ Tech Stack & Dependencies

* **Runtime Environment:** Node.js
* **Web Framework:** Express.js
* **Templating Engine:** EJS
* **HTTP Client:** Axios
* **Middleware:** Body-Parser

---

## 📡 REST API Endpoints (Port 4000)

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/posts` | Retrieve all blog posts |
| `GET` | `/posts/:id` | Retrieve a specific blog post by ID |
| `POST` | `/posts` | Create a new blog post |
| `PATCH` | `/posts/:id` | Partially update an existing blog post |
| `DELETE` | `/posts/:id` | Delete a specific blog post by ID |

---

## 🚀 How to Run the Application

### 1. Install Dependencies
Run this command in the project root to install all required packages (`express`, `axios`, `ejs`, `body-parser`):
```bash
npm install
