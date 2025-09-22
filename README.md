# Movie-Site Backend

Backend service for the **Movie-Site** project.  
Implements a REST API with **Node.js + Express**, structured with `api/` (routes + controllers) and `dao/` (MongoDB data access).  
This was my **introductory backend project**, giving me first exposure to server setup, request handling, and database interaction.  

---

## 🚀 Features
- RESTful API endpoints for managing movie reviews  
- **Controller layer** to handle business logic  
- **Routes layer** to define API endpoints  
- **DAO (Data Access Object)** for MongoDB persistence  
- JSON request/response handling with Express  
- Environment variable configuration (`dotenv`)  

---

## 📂 Project Structure
```
movie-site-backend/
├── api/
│   ├── reviews.controller.js   # Handles review logic
│   └── reviews.route.js        # API route definitions
├── dao/
│   └── reviewsDAO.js           # MongoDB data access
├── server.js                   # Express app + middleware
├── index.js                    # Entry point
├── package.json                # Dependencies + scripts
└── README.md                   # Documentation
```

---

## 🛠️ Tech Stack
- **Node.js** — runtime  
- **Express.js** — REST API framework  
- **MongoDB Atlas** — database (DAO layer for CRUD)  
- **dotenv** — environment configuration  

---

## ⚙️ Setup
1. Clone the repo:  
   ```bash
   git clone https://github.com/JihanChowdhury334/movie-site-backend.git
   cd movie-site-backend
   ```

2. Install dependencies:  
   ```bash
   npm install
   ```

3. Configure environment:  
   - Create a `.env` file with your MongoDB connection string  
   - Example:  
     ```
     MONGO_URI=your-mongo-uri
     PORT=5000
     ```

4. Start the server:  
   ```bash
   npm start
   ```

---

## 📈 Learning Purpose
This was my **first backend project**, built while following a guided tutorial.  
It helped me understand:
- Express route/controller separation  
- Connecting Node.js apps to MongoDB via a DAO pattern  
- Handling CRUD operations in a REST API  
- Using environment variables securely  

⚠️ Note: Built purely as a learning project, not production-ready.
