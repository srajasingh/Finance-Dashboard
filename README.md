# 📊 Finance Dashboard  - https://finance-dashboard-project.vercel.app/

## 🚀 Overview  
Finance Dashboard is a **full-stack web application** designed to help users manage their expenses efficiently. It provides insights into financial data through interactive visualizations, real-time tracking, and budget management features.  

 ![picture](https://github.com/user-attachments/assets/d6a7e00b-5ab5-4f11-a14c-a2c58a4e5b7a)

## 📂 Project Structure  
```
Finance-Dashboard/
│── client/              # Frontend (React.js)
│── server/              # Backend (Node.js, Express)
│── database/            # MongoDB Integration
│── Dockerfile           # Docker containerization
│── vercel.json          # Vercel deployment configuration
│── README.md            # Documentation
└── package.json         # Dependencies and scripts
```

## 🛠️ Technologies Used  
### **Frontend:**  
- React.js  
- Tailwind CSS  
- Axios  
- Chart.js  

### **Backend:**  
- Node.js  
- Express.js  
- MongoDB (Atlas)  
- Mongoose  
- JWT Authentication  
- Bcrypt  

### **DevOps & Deployment:**  
- **Vercel** for frontend and backend deployment  
- **GitHub Actions** for CI/CD  
- **Docker & Kubernetes** for containerization  
- **Postman** for API testing  

## 🔥 Features  
✅ **User Authentication:** Secure login & registration with JWT  
✅ **Expense Tracking:** Categorized expense tracking with real-time updates  
✅ **Data Visualization:** Interactive charts for financial insights  
✅ **Budget Management:** Set monthly budgets & track spending  
✅ **Secure Transactions:** Encrypted data storage & security measures  
✅ **Cloud Storage:** Sync data across devices  

## 📜 Installation Guide  
### **Prerequisites:**  
- Node.js & npm installed  
- MongoDB Atlas setup  


### **2️⃣ Backend Setup**  
```bash
cd server
npm install
```
#### **Environment Variables**  
Create a `.env` file in the `server` directory and add:  
```
MONGO_URL=your_mongodb_url
JWT_SECRET=your_secret_key
```
Run the backend:  
```bash
npm start
```

### **3️⃣ Frontend Setup**  
```bash
cd ../client
npm install
npm start
```

### **4️⃣ Deployment**  
To deploy on **Vercel**, run:  
```bash
vercel deploy
```

## 🎯 Future Enhancements  
🔹 AI-based expense prediction  
🔹 Multi-user collaboration  
🔹 Mobile App version  

## 📌 Contribution  
Contributions are welcome! Feel free to fork the repo and submit pull requests.  


