# campingBazzar--Web-Guide
---

Welcome to **Camping Bazaar**, a platform for buying, selling, and exchanging camping gear. This project is divided into two parts:  

1. **Front-end**: Built with React.js  
2. **Back-end**: Powered by Express.js  

Follow the steps below to set up and run the projects locally.

---

## 🚀 Getting Started  

### Prerequisites  
Make sure you have the following installed on your system:  

- [Node.js](https://nodejs.org/) (v16 or above)  
- [npm](https://www.npmjs.com/) (comes with Node.js)  
- [Git](https://git-scm.com/)  

---

## 📂 Project Structure  

- **Front-end**: [CampingBazzar--WEB-](https://github.com/Aniisss/CampingBazzar--WEB-/tree/feat)  
- **Back-end**: [campingBazzar--backend](https://github.com/Aniisss/campingBazzar--backend)  

---

## 🔧 Installation  

### Front-end Setup  

#### 1️⃣ Clone the Repository  

```bash
# Clone the front-end repository
git clone https://github.com/Aniisss/CampingBazzar--WEB-.git
cd CampingBazzar--WEB-
git checkout feat
```

#### 2️⃣ Install Dependencies  

```bash
npm install
```

#### 3️⃣ Start the Application  

```bash
npm start
```

The React app will run on [http://localhost:3000](http://localhost:3000).  

---

### Back-end Setup  

#### 1️⃣ Clone the Repository  

```bash
# Clone the back-end repository
git clone https://github.com/Aniisss/campingBazzar--backend.git
cd campingBazzar--backend
```

#### 2️⃣ Install Dependencies  

```bash
npm install
```

#### 3️⃣ Configure Environment

Add a `service-account.json` file in the `campingBazzar--backend/src/config` directory  


#### 4️⃣ Start the Server  

```bash
node index.js -port 5000`

The server will run on [http://localhost:5000](http://localhost:5000).  
```
---

## 🌐 Access the Application  

1. Open your browser and visit [http://localhost:3000](http://localhost:3000) to access the front-end.  
2. The front-end communicates with the back-end running on [http://localhost:5000](http://localhost:5000).  

**Note: The current front app on github is communicating with the hosted backend on  [http://20.64.237.50:3000](http://20.64.237.50:3000) wich means running the backend locally isn't mandatory and if so it won't make a difference**

---

## 🛠️ Development  

- **Front-end**: React components are located in the `src/components/` directory.  
- **Back-end**: API routes are in the `src/routes/` folder.  

---

## ✨ Features  

- Buy, sell, and exchange camping gear.  
- User authentication and messaging.  
- Discussion forums for camping enthusiasts.  
- See product details and manage favorites.  

---
Happy Camping! 🏕️  
