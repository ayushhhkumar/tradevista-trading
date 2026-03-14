# Zerodha Clone – Full Stack Trading Dashboard

A **full-stack stock trading dashboard inspired by Zerodha Kite**, built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**.

The application simulates a trading platform where users can view their portfolio, monitor holdings and positions, and place buy orders through an interactive dashboard.

This project demonstrates **full-stack development, REST API design, database integration, and cloud deployment**.

## Live Application

**Frontend (Landing Page)**
https://zerodha-frontend-3qfs.onrender.com

**Trading Dashboard**
https://zerodha-dashboard-gtnk.onrender.com

**Backend API**
https://zerodha-backend-wrhv.onrender.com

## Tech Stack

### Frontend

* React.js
* Material UI
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas

### Deployment

* Render

## Key Features

* Portfolio dashboard displaying stock holdings
* View and track open trading positions
* Place buy orders through the dashboard
* RESTful API integration between frontend and backend
* Interactive portfolio visualization with charts
* Modular project architecture

## Project Structure

```
ZERODHA-CLONE
│
├── frontend
│   └── Landing page built with React
│
├── dashboard
│   └── Trading dashboard interface
│
├── backend
│   └── Express API connected to MongoDB
│
└── README.md
```

## API Endpoints

| Method | Endpoint      | Description              |
| ------ | ------------- | ------------------------ |
| GET    | /allHoldings  | Fetch all stock holdings |
| GET    | /allPositions | Fetch open positions     |
| POST   | /newOrder     | Create a new buy order   |

## Running the Project Locally

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/zerodha-clone.git
cd zerodha-clone
```

### Install backend dependencies

```bash
cd backend
npm install
```

Create a `.env` file inside the backend folder:

```
MONGO_URL=your_mongodb_connection_string
PORT=3002
```

Run backend server

```bash
node index.js
```

### Run Dashboard

```bash
cd dashboard
npm install
npm start
```

### Run Frontend

```bash
cd frontend
npm install
npm start
```

## Future Improvements

* User authentication system
* Real-time stock market data integration
* Portfolio analytics dashboard
* Mobile responsive improvements
* WebSocket-based live updates

## Author

Ayush Kumar

GitHub:
https://github.com/ayushhhkumar

## License

This project is developed for **learning and portfolio purposes**.
