# Blood Bank Management System
 
**Blood Bank Management System** built using the **MERN stack**:  

---

## 🩸 Blood Bank Management System 🏥  

A **Blood Bank Management System** built using the **MERN stack (MongoDB, Express.js, React, Node.js)** that enables efficient blood donation, request, and inventory management.  

### 🚀 Features  
✔ **Donor Registration** – Users can register as donors and provide their blood group, location, and availability.  
✔ **Blood Request Management** – Patients and hospitals can request blood by specifying the required type and urgency.  
✔ **Inventory Tracking** – Admins can manage blood stock levels, ensuring availability.  
✔ **Search & Filter** – Users can search for donors or blood availability by location and blood type.  
✔ **Authentication & Authorization** – Secure login and access control using JWT authentication.  
✔ **Real-time Notifications** – Alerts for new blood requests and donor matches.  
✔ **Admin Dashboard** – View and manage users, donations, and inventory.  

### 🛠 Tech Stack  
- **Frontend**: React.js, Tailwind CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (Mongoose)  
- **Authentication**: JWT & bcrypt  
- **State Management**: Redux (if needed)  
- **Deployment**: Vercel (Frontend), Render/Heroku (Backend), MongoDB Atlas  



### 🏗 Installation & Setup  
#### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/blood-bank-management.git
cd blood-bank-management
```
#### 2️⃣ Install Backend Dependencies  
```bash
cd backend
npm install
```
#### 3️⃣ Install Frontend Dependencies  
```bash
cd ../frontend
npm install
```
#### 4️⃣ Set up Environment Variables  
Create a `.env` file in the `backend` directory and add:  
```plaintext
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

#### 5️⃣ Run the Application  
- **Backend:**  
```bash
cd backend
npm start
```
- **Frontend:**  
```bash
cd frontend
npm start
```

### 📜 License  
This project is open-source and available under the **MIT License**.

---

