# Book-store-MERN
Project on MERN Stack For SmartInternz 


# 📚 Book Store Web Application (MERN Stack)

A full-stack Book Store web application built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. Users can register, log in, browse available books, add them to their cart, and checkout. Admins can manage books, users, and orders.

---

## 🚀 Features

- 🔐 User Authentication 
- 🛒 Shopping Cart and Checkout
- 📚 Book Management 
- 👤 User Dashboard
- 🧾 Order Management
- 🛠 Admin Panel
- 🔎 Book Search and Filtering
- 📱 Responsive UI with React

---

## 🧰 Tech Stack

**Frontend**:
- React.js
- Redux
- React Router DOM

**Backend**:
- Node.js
- Express.js
- MongoDB (Mongoose ODM)



---

## ⚙️ Setup Instructions

### Prerequisites
- Node.js (v14+)
- MongoDB (Local or Atlas)

### Clone the Repo

git clone https://github.com/fanishkdiwan/Book-store-MERN.git
cd Book-store-MERN

How to run this project:


For Frontend
Follow the below steps to run the project:

Firstly clone or unzip the project folder.
Go to the frontend directory by using the following command cd frontend.
create a .env.local file in the backend root directory as the same level where the package.json is located and keep the following environment variables there:


>>> Stepup firebase app and configure the environment

VITE_API_KEY="AIzaSyCXvDIC4MPrkaMdeg_O2iij88wLpfj3qBA"
VITE_Auth_Domain="book-store-mern-app.firebaseapp.com"
VITE_PROJECT_ID="book-store-mern-app"
VITE_STORAGE_BUCKET="book-store-mern-app.appspot.com"
VITE_MESSAGING_SENDERID= "205632822247"
VITE_APPID="1:205632822247:web:b0db0ec66bf6de0bbb3b42"

Then run npm install commend to install node dependencies.
Finally, to run the project, use npm run dev command.
For Backend
Follow the below steps to run the project:

Firstly clone or unzip the project folder.
Go to the backend directory by using the following command  cd backend.
Then run npm install commend to install node dependencies.
create a .env file in the backend root directory as the same level where the package.json is located and keep the following environment variables there:


DB_URL = "mongodb+srv://helpyourassistant:pqam0Mwv3Vwv8Off@cluster0.qc3bq.mongodb.net/book-store?retryWrites=true&w=majority&appName=Cluster0"

JWT_SECRET_KEY = 'bc992a20cb6706f741433686be814e3df45e57ea1c2fc85f9dbb0ef7df12308a669bfa7c976368ff32e32f6541480ce9ec1b122242f9b1257ab669026aeaf16'

Note: Please setup mongodb and change the MongoDB url and set your jwt secret key above.

Finally, to run the project, use npm run start:dev command.
