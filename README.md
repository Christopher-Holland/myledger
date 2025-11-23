# My Ledger

**My Ledger** is a full-stack personal finance manager built with the MERN stack (MongoDB, Express, React, Node.js). It helps users track bills, set financial goals, and visualize spending patterns through an interactive dashboard.

---

## Features

- User authentication with **JWT** for secure login and registration
- CRUD operations for bills, goals, and expenses
- Interactive dashboard with charts and visual analytics
- Responsive design for desktop and mobile
- Full deployment: backend on **Render**, frontend on **Vercel**

---

## Tech Stack

- **Frontend:** React, TailwindCSS, Vite
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT, bcrypt
- **Tools:** Git, GitHub, Postman
- **Deployment:** Render (backend), Vercel (frontend)

---

## Live Demo

[Try it live here](https://my-ledger-cholland.vercel.app/)

---

## Getting Started

### Prerequisites

- Node.js >= 18
- npm or yarn
- MongoDB instance (local or cloud, e.g., MongoDB Atlas)

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Christopher-Holland/myledger.git
cd myledger
```

2. **Install backend dependencies:**

```bash
cd backend
npm install
```

3. **Install frontend dependencies:**

```bash
cd ../frontend
npm install
```

4. **Create a `.env` file in the `backend` folder** with the following content:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

5. **Start the backend server:**

```bash
cd backend
npm start
```

6. **Start the frontend development server:**

```bash
cd ../frontend
npm start
```

7. **Open the app in your browser:**  
Visit [http://localhost:5173](http://localhost:5173)

---

## Folder Structure

```
myledger/
├── backend/          # Node.js + Express API
├── frontend/         # React + TailwindCSS frontend
├── README.md         # Project documentation
```

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## License

This project is licensed under the MIT License.

---

## Contact

- GitHub: [Christopher-Holland](https://github.com/Christopher-Holland)  
- Portfolio: [christopher-holland.github.io/portfolio](https://christopher-holland.github.io/portfolio/)

<img width="432" height="650" alt="image" src="https://github.com/user-attachments/assets/a90e6c61-0b53-43e6-ad62-cbbbe868e92f" />
