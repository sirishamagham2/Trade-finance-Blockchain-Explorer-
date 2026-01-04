# Trade-finance-Blockchain-Explorer-

Description...
Trade Finance Blockchain Explorer
📌 Project Description
The Trade Finance Blockchain Explorer is a backend system designed to manage and track trade finance transactions using blockchain technology.
This project provides secure REST APIs to store, retrieve, and explore blockchain-based trade finance records such as invoices, shipments, smart contracts, and transactions.
The application is developed using FastAPI and follows modern backend architecture with secure authentication, modular code design, and scalable database integration.
It ensures data security using JWT authentication and supports protected API endpoints for authorized users.
🛠 Technologies Used
Technology
Purpose
FastAPI
Backend REST API
SQLModel
Database ORM
SQLite / PostgreSQL
Database
PyJWT
JWT Authentication
Passlib
Password Hashing
Uvicorn
ASGI Server
📂 Project Structure
app/
 ├ main.py
 ├ database.py
 ├ models.py
 ├ auth.py
 ├ routes/
 │    └ auth.py
 └ core/
      └ security.py
## How to run
1. Clone the Repository
git clone https://github.com/sirishamagham2/Trade-finance-Blockchain-Explorer-.git
cd Trade-finance-Blockchain-Explorer-
2. Create Virtual Environment
python -m venv venv
3.bWindows
venv\Scripts\activate
4. Linux / Mac
source venv/bin/activate
3. Install Requirements
pip install -r requirements.txt
4. Run the Server
uvicorn app.main:app --reload
5. Open API Docs
Open in browser:

http://127.0.0.1:8000/docs
...
🔐 Authentication Endpoints
Endpoint
Method
Description
/login
POST
User login
/refresh
POST
Refresh access token

AUTHOR 
Magham Sirisha
Backend Development Intern
