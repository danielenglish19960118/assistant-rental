# Assistant Rental Application

A web application for assistant rental services, built with Node.js and containerized using Docker.

## 📋 Table of Contents

- [Features](#-features)
- [Project Structure](#-project-structure)
- [Prerequisites](#-prerequisites)
- [Getting Started](#-getting-started)
  - [Local Setup](#local-setup)
  - [Docker Setup](#docker-setup)
- [License](#-license)

---

## ✨ Features

- Lightweight Node.js express server logic (`server.js`)
- Static front-end assets delivered via `public/index.html`
- Docker containerization ready out-of-the-box

---

## 📁 Project Structure

```text
assistant-rental/
├── Dockerfile           # Docker configuration file
├── package.json         # Node.js dependencies and scripts
├── public/              # Public directory for static files
│   └── index.html       # Front-end HTML interface
├── server.js            # Node.js server entry point
└── README.md            # Project documentation
```

---

## 🛠️ Prerequisites

Before running this project, ensure you have the following installed on your local machine:

- **Node.js** (v14.x or higher)
- **npm** (Node Package Manager)
- **Docker** *(optional, required only for running in container)*

---

## 🚀 Getting Started

### Local Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/assistant-rental.git
   cd assistant-rental
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the server:**
   ```bash
   npm start
   ```
   *(or run `node server.js` directly)*

4. Open your browser and navigate to `http://localhost:3000` (or your configured port).

---

### Docker Setup

1. **Build the Docker image:**
   ```bash
   docker build -t assistant-rental .
   ```

2. **Run the container:**
   ```bash
   docker run -p 3000:3000 assistant-rental
   ```

3. Access the application at `http://localhost:3000`.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
