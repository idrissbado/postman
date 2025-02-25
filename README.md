# Node.js API Server

This project is a Node.js-based API server that demonstrates CRUD (Create, Read, Update, Delete) operations. It includes server configuration, models, and Postman test images for API endpoints.

---

## Project Structure

| File/Folder         | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `config/`           | Contains configuration files for the server.                                |
| `models/`           | Includes data models used in the application.                               |
| `node_modules/`     | Contains installed dependencies (auto-generated by npm).                    |
| `DELETE.jpg`        | Postman test image for DELETE requests.                                     |
| `GET.jpg`           | Postman test image for GET requests.                                        |
| `POST.jpg`          | Postman test image for POST requests.                                       |
| `POST 2.jpg`        | Additional Postman test image for POST requests.                            |
| `POST 3.jpg`        | Additional Postman test image for POST requests.                            |
| `PUT.jpg`           | Postman test image for PUT requests.                                        |
| `Server.js`         | Main server file that handles API routes and logic.                         |
| `package.json`      | Contains project metadata and dependencies.                                 |
| `package-lock.json` | Auto-generated file for dependency versioning.                              |

---

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (Node Package Manager)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/idrissbado/postman.git
   cd postman

2.**Install Dependencies**
npm install
3.**Start the server**
node Server.js
| HTTP Method | Endpoint         | Description                          |
|-------------|------------------|--------------------------------------|
| GET         | `/api/data`      | Fetch all data.                      |
| POST        | `/api/data`      | Create new data.                     |
| PUT         | `/api/data/:id`  | Update data by ID.                   |
| DELETE      | `/api/data/:id`  | Delete data by ID.                   |
