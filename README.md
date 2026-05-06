# 🩸 Blood Bank with Philanthropic Matchmaker (Cloud-Based System)

> A cloud-powered blood bank management system that connects donors, hospitals, and patients in real time for efficient blood matching and emergency response.

---

## 📖 Description

This project is a cloud-based blood bank management system designed to streamline the process of blood donation and distribution. It connects donors, recipients, hospitals, and blood banks through a centralized platform.

The system enables users to quickly search for available blood based on location and blood group, ensuring faster response during emergency situations. It also allows hospitals to manage blood inventory and handle requests efficiently.

By leveraging cloud computing, the application ensures secure data storage, real-time access, and improved coordination between all stakeholders in the healthcare ecosystem.

---

## 🚀 Features

- 🩸 Real-time blood donor and blood bank management  
- 📍 Location-based donor search  
- 🔔 Emergency blood request and notification system  
- 🏥 Hospital dashboard for blood inventory management  
- 👤 Donor registration and verification  
- ☁️ Cloud-based secure data storage  
- 🔍 Fast blood availability search  

---

## 📂 Use Cases

- Emergency blood requirement handling  
- Hospital blood inventory management  
- Connecting voluntary donors with patients  
- Cloud-based healthcare data management  

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP (Laravel)  
- **Database:** MySQL  
- **Cloud:** AWS (EC2)  
- **Other:** REST APIs, Linux  

---

## 🌟 System Modules

### 👤 Donor Module
- Register as a donor  
- Update blood group and location  
- View donation requests  
- Respond to emergency alerts  

### 🧑‍⚕️ Receiver Module
- Register and login  
- Search for required blood group  
- View nearby donors and blood banks  
- Send blood requests  

### 🏥 Hospital Module
- Manage blood inventory  
- Accept or reject requests  
- Update available blood units  

### 🔐 Admin Module
- Verify donor accounts  
- Manage users and hospitals  
- Monitor system activity  
- Maintain database security  

---

## ⚙️ How It Works

1. Users (donor/receiver) register in the system  
2. Donor data is stored in a cloud database  
3. Receiver requests a specific blood group  
4. System checks availability in:
   - Blood banks  
   - Registered donors  
5. Nearby donors are displayed  
6. Notifications are sent  
7. Blood donation is completed  

---

## ☁️ Cloud Architecture

- Application hosted on AWS EC2  
- MySQL database for storing data  
- Web interface for user interaction  
- Real-time data processing for quick response  

---

## 📸 Screenshots

- Home Page  
- Donor Registration  
- Blood Request Page  
- Donor List  
- Admin Dashboard  

*(Add images in `/screenshots` folder)*

---

## 📦 Project Setup

### Step 1: Clone Repository

git clone https://github.com/your-username/blood-bank-cloud-system.git
cd blood-bank-cloud-system

## 📦 Project Setup

### Step 2: Setup Environment

Requirements:

- PHP (>= 7.x)  
- MySQL  
- Composer  
- XAMPP / Laravel  

---

### Step 3: Install Dependencies

composer install

Step 4: Configure Database

Update .env file:

DB_DATABASE=your_db
DB_USERNAME=root
DB_PASSWORD=your_password

Step 5: Run Project

php artisan serve

Open browser:

http://127.0.0.1:8000

📁 Directory Structure

blood-bank-cloud-system/
│
├── app/                  
├── public/               
├── resources/            
├── routes/               
├── database/             
├── .env                  
├── README.md             
└── composer.json

## 🔍 Key Functionalities

- Blood group filtering  
- Location-based donor search  
- Real-time request processing  
- Secure cloud data storage  

---

## ⚠️ Challenges Faced

- Ensuring data security in healthcare systems  
- Efficient donor-recipient matching  
- Handling real-time emergency requests  

---

## 📈 Future Enhancements

- 📱 Mobile application  
- 🔔 SMS/Email notifications  
- 🤖 AI-based donor matching  
- 📍 Live location tracking  

---

## 🎯 Conclusion

This project demonstrates how cloud computing can enhance healthcare services by improving blood donation management and reducing response time during emergencies. It ensures efficient coordination between donors, hospitals, and patients.

---

## 👨‍💻 Author

**Dino Giftlin Daniel**  
MCA – Cloud Computing  
Hindustan Institute of Technology and Science  
