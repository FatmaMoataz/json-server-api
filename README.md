# 📄 License
This project is for educational and internship purposes.


# JSON Server API – Medical Center App 🖥️

This is a mock REST API built using **JSON Server** to support the frontend of the Medical Center Website project. It simulates a simple database for storing appointment data.

## 🔗 Live API

➡️ [https://json-server-api-production-9295.up.railway.app/appointments](https://json-server-api-production-9295.up.railway.app/appointments)

---

## 📦 Tech Stack

- Node.js
- JSON Server
- Hosted on Railway

---

## 📁 Project Structure

├── db.json # Main data storage


├── server.js # JSON Server configuration


├── README.md # This file


├── package.json # Project setup


---

## 📄 Endpoints

- `GET /appointments` – Get all appointments
- `POST /appointments` – Add a new appointment
- `PUT /appointments/:id` – Edit an appointment
- `DELETE /appointments/:id` – Delete an appointment

> Note: The frontend uses a basic email prompt (modal) to simulate protection before allowing edit/delete.

---

## 🚀 Getting Started (Locally)

```bash
git clone https://github.com/FatmaMoataz/json-server-api.git
cd json-server-api
npm install
npm start
```

⚠️ Hosting Notes
The API is hosted on Railway (free tier) which may sleep or lose data after inactivity.

You can re-upload seed data manually or use a script if needed.


