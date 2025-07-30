Frontend (Client)
React.js (JSX)

React Router for navigation

Backend (Server)
Spring Boot (Java)

Spring Security (JWT Authentication)

Spring Data JPA for database interaction

MySQL for data storage

Razorpay API for payments

Spring Mail for email notifications

📂 Project Structure
css
Copy
Edit
SalesSavvy/
├── SS-FE/                   # Frontend (React.js)
│   ├── src/
│   ├── public/
│   ├── package.json
│   ├── vite.config.js
│   ├── README.md
├── SS-BE/                   # Backend (Spring Boot)
│   ├── src/main/java/
│   ├── src/main/resources/
│   ├── pom.xml
│   ├── README.md
├── docker-compose.yml
├── .gitignore
├── README.md
🚀 Getting Started
🛠 Prerequisites
Before running the project, install the following:

Node.js (for frontend)

Java 17+ (for backend)

MySQL (Database)

Docker (Optional)

📦 Backend Setup
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/vishnu-in-sane/Sales-savy.git
cd SalesSavvy/SS-BE
2️⃣ Set Up MySQL Database
Create a database:

sql
Copy
Edit
CREATE DATABASE sales_savvy;
Then configure your database in application.properties:

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/sales_savvy  
spring.datasource.username=root  
spring.datasource.password=Vishnu@1979  
spring.jpa.hibernate.ddl-auto=update
3️⃣ Run the Backend
bash
Copy
Edit
mvn clean install  
mvn spring-boot:run
✅ Backend will start on: http://localhost:9090

🎨 Frontend Setup
1️⃣ Navigate to Frontend Directory
bash
Copy
Edit
cd SalesSavvy/SS-FE
2️⃣ Install Dependencies
bash
Copy
Edit
npm install
3️⃣ Run the Frontend
bash
Copy
Edit
npm run dev
✅ Frontend will start on: http://localhost:5174

🔗 API Endpoints
🔐 Authentication
POST /api/auth/register → User Registration

POST /api/auth/login → User Login

POST /api/auth/logout → Logout User

📦 Products
GET /api/products → Fetch all products

GET /api/products/{id} → Get product by ID

POST /api/products → Add new product (Admin only)

🛒 Cart
POST /api/cart/add → Add item to cart

GET /api/cart → View cart items

📦 Orders
POST /api/orders → Place an order

GET /api/orders/{userId} → Get user orders

🐳 Running with Docker
1️⃣ Build and Run with Docker Compose
bash
Copy
Edit
docker-compose up --build
2️⃣ Stop the Containers
bash
Copy
Edit
docker-compose down
📜 Git Workflow
🚀 First-Time Setup
bash
Copy
Edit
git init
git remote add origin https://github.com/vishnu-in-sane/Sales-savy.git
git branch -M main
git pull origin main
🌟 Push New Changes
bash
Copy
Edit
git add .
git commit -m "Your commit message"
git push origin main
⬇️ Fetch Latest Changes
bash
Copy
Edit
git pull origin main
📢 Contributing
🚀 Contributions are welcome! If you'd like to contribute:

Fork the repository

Create a new branch (git checkout -b feature-branch)

Commit changes (git commit -m "Added new feature")

Push to your branch (git push origin feature-branch)

Open a Pull Request

📞 Contact
📧 Email: vishnuvaibhav339@gmail.com

📱 Phone: 9663063488

🌐 GitHub: https://github.com/vishnu-in-sane

