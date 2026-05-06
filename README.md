🩸 Blood Bank with Philanthropic Matchmaker (Cloud-Based System)

A cloud-based blood bank management system that connects donors, recipients, hospitals, and blood banks to ensure timely blood availability during emergencies.

🚀 Features
🩸 Real-time blood donor and blood bank management
📍 Find nearby donors based on blood group and location
🔔 Emergency blood request and notification system
🏥 Hospital dashboard to manage blood inventory
👤 Donor registration and verification system
☁️ Cloud-based secure data storage
🔍 Quick search for blood availability
📂 Use Cases
Emergency blood requirement handling
Hospital blood inventory management
Connecting voluntary blood donors with patients
Healthcare data management using cloud computing
🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: PHP (Laravel)
Database: MySQL
Cloud: AWS (EC2 / Cloud Hosting)
Other: REST APIs, Linux
🌟 System Modules
👤 Donor Module
Register as a donor
Update personal details (blood group, location)
View donation requests
Respond to emergency needs
🧑‍⚕️ Receiver Module
Register and login
Search for required blood group
View nearby donors and blood banks
Send blood request
🏥 Hospital Module
Manage blood stock
Accept or reject blood requests
Update availability of blood units
🔐 Admin Module
Verify donors
Manage users and hospitals
Monitor system activity
Maintain database security
⚙️ How It Works
User (donor/receiver) registers in the system
Donor details are stored securely in cloud database
Receiver requests a specific blood group
System checks availability in:
Blood banks
Registered donors
Nearby donors are displayed
Notifications are sent for quick response
Blood donation is completed
☁️ Cloud Architecture (High Level)
Application hosted on cloud server (AWS EC2)
MySQL database stores donor, hospital, and request data
Users access system via web interface
Real-time data retrieval for faster response
📸 Screens (Optional - you can add images later)
Home Page
Donor Registration Page
Blood Request Page
Donor List Page
Admin Dashboard
📦 Project Setup
Step 1: Clone the Repository
git clone https://github.com/your-username/blood-bank-cloud-system.git
cd blood-bank-cloud-system
Step 2: Setup Environment

Make sure you have:

PHP (>= 7.x)
MySQL
Composer
XAMPP / Laravel setup
Step 3: Install Dependencies
composer install
Step 4: Configure Database
Create a MySQL database
Update .env file:
DB_DATABASE=your_db
DB_USERNAME=root
DB_PASSWORD=your_password
Step 5: Run the Project
php artisan serve
Open in browser:
http://127.0.0.1:8000
📁 Directory Structure
blood-bank-cloud-system/
│
├── app/                  # Laravel backend logic
├── public/               # Frontend assets
├── resources/            # Views (UI pages)
├── routes/               # API and web routes
├── database/             # Migrations
├── .env                  # Configuration
├── README.md             # Project documentation
└── composer.json         # Dependencies
🔍 Key Functionalities
Blood group-based filtering
Location-based donor search
Real-time request handling
Secure data management using cloud

⚠️ Challenges Faced
Data security in healthcare systems
Matching donors efficiently
Handling real-time emergency requests

📈 Future Enhancements
📱 Mobile application (Android/iOS)
🔔 SMS/Email notification integration
🤖 AI-based donor prediction system
📍 GPS live tracking for donors

🎯 Conclusion

This project demonstrates how cloud computing can improve healthcare services by enabling efficient blood donor management and faster emergency response. It reduces the time required to find donors and ensures better coordination between hospitals and patients.

👨‍💻 Author

Dino Giftlin Daniel
MCA – Cloud Computing
Hindustan Institute of Technology and Science
