# car-rental
A full-stack Car Rental Web Application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). Users can add cars, view cars, manage availability, and rent cars in a seamless and responsive UI.


📌 Features
👤 User Features

View available cars

Rent a car

Check car availability

Booking confirmation

🚗 Admin Features

Add new cars

Edit or delete car listings

Manage rental history

Control car availability

🧩 Technical Features

MERN architecture

RESTful API integration

MongoDB for storing car data & rentals

Form validation & error handling

Responsive UI (React + Vite)

🛠️ Tech Stack

Frontend:

React.js

Vite

Axios

CSS / Tailwind (if used)

Backend:

Node.js

Express.js

MongoDB + Mongoose

dotenv

Multer (if you upload images)

📂 Project Structure
carRental/
│── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── uploads/
│   │   └── index.js
│   ├── .env
│   ├── package.json
│   └── README.md
│
│── frontend/
│   ├── src/
│   ├── public/
│   ├── vite.config.js
│   ├── package.json
│   └── README.md
│
└── README.md (main)

🚀 How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/your-username/car-rental.git
cd car-rental

🔧 2️⃣ Setup Backend
cd backend
npm install


Create a .env file:

MONGO_URI=your_mongodb_connection_string
PORT=5000


Start backend:

npm start


Backend runs at:
👉 http://localhost:5000

🎨 3️⃣ Setup Frontend
cd ../frontend
npm install
npm run dev


Frontend runs at:
👉 http://localhost:5173
