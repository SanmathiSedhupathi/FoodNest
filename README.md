

# 🍽️ RecipeNest

**RecipeNest** is a full-stack recipe sharing web application built with the **MERN stack** (MongoDB, Express.js, React.js, and Node.js). It allows users to create, explore, and share culinary recipes with ingredients, instructions, and images. The app is designed to be simple, intuitive, and responsive for all food lovers.

---

## 🚀 Features

- ✅ Add and share your favorite recipes
- 📸 Upload images for recipes
- 🔍 Search and filter recipes by title or ingredients
- 📝 View complete recipe instructions and ingredients
- 💾 Store recipes in MongoDB
- 📱 Fully responsive design using **Bootstrap 5**

---

## 🛠️ Tech Stack

| Layer       | Technology          |
|-------------|---------------------|
| **Frontend**  | React.js, Bootstrap 5, CSS |
| **Backend**   | Node.js, Express.js       |
| **Database**  | MongoDB Atlas             |
| **Tools**     | Axios, dotenv, UUID, Multer (optional for file uploads)

---

## 📂 Project Structure

RecipeNest/   
├── client/ # React frontend  
│ ├── public/   
│ └── src/  
│ ├── components/  
│ ├── pages/  
│ ├── App.js  
│ └── index.js  
├── server/ # Express backend  
│ ├── controllers/  
│ ├── models/  
│ ├── routes/   
│ ├── server.js  
│ └── .env  
├── README.md  
└── package.json  


---

## ⚙️ Getting Started

### 📥 1. Clone the Repository

```bash
git clone https://github.com/SanmathiSedhupathi/RecipeNest.git
cd RecipeNest
```

### 🔧 2. Backend Setup
```bash
cd server
npm install
```
Create a .env file in the server directory:

```bash
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```
Run the backend server:

```bash
npm run dev
``` 

### 💻 3. Frontend Setup

```bash
cd ../client
npm install
npm start
```
The frontend will run on: http://localhost:3000

🌐 Live Demo
🚧 Coming soon...

🙏 Acknowledgements
- MongoDB Atlas

- React.js

- Express.js

- Bootstrap

- Node.js

📄 License  
This project is licensed under the MIT License.

