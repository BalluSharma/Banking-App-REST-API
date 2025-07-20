# Banking-App-REST-API
💰 Banking App 🏦
This is a Backend-only application created using Spring Boot ☕. The project demonstrates a simple banking system with functionalities like account management, withdrawals, transfers, credits, debits, and transaction history — all connected to a MySQL database 🗄️ and tested using Postman 📬.

🔧 Technologies Used
🧠 Backend: Spring Boot

💾 Database: MySQL

🧪 API Testing: Postman

🚀 Features
✨ Built with REST APIs using:

@GetMapping 🔍

@PostMapping ➕

@PutMapping 🔁

@DeleteMapping ❌

🧾 Core Banking Operations:

🔎 View account information

💸 Withdraw money

💳 Credit money

🏦 Transfer funds between accounts

🧮 Debit money

📜 View transaction history

⚙️ Getting Started
To run this project locally:

🔽 Clone the repository

🛠️ Configure your application.properties with your MySQL credentials

▶️ Run the application using:

bash
mvn spring-boot:run

📬 API Endpoints (Use with Postman)
Method	Endpoint	Description
GET	/api/accounts	Get all accounts 🧾
POST	/api/accounts	Create a new account ➕
GET	/api/accounts/{id}	Get account by ID 🔍
PUT	/api/accounts/{id}	Update account info 🔧
DELETE	/api/accounts/{id}	Delete an account ❌
POST	/api/accounts/{id}/withdraw	Withdraw from account 💸
POST	/api/accounts/{id}/transfer	Transfer between accounts 🔁
POST	/api/accounts/{id}/credit	Credit account 💳
POST	/api/accounts/{id}/debit	Debit account 🧮
GET	/api/accounts/{id}/transactions	View transaction history 📜

🤝 Contributing
Feel free to fork 🔀 this repo and contribute by submitting pull requests 🚀
For major changes, please open an issue first 📌

📄 License
This project is licensed under the MIT License 📝

🔖 Hashtags
#SpringBoot ☕ #Java #MySQL 🗄️ #Postman #RESTAPI #BankingApp 🏦 #BackendDevelopment #OpenSource 🚀
