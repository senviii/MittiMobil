# 🌾 MittiMobil – Empowering Rural Transport

MittiMobil is an innovative backend solution that brings the **Uber/Rapido-like real-time availability system** to rural India — but for tractors, harvesters, and other essential agricultural equipment 🚜. Farmers can view available tools nearby, rent them on-demand, and increase productivity by sharing resources. 

---

## 📌 Features

- ✅ **Equipment Availability Tracking** – Real-time status of tractors, tillers, harvesters, and more.
- 📍 **Location-Based Services** – Track & assign based on GPS zones or panchayat boundaries.
- 🧑🏽‍🌾 **Farmer Profiles** – Register, authenticate, and manage your availability & bookings.
- 🕒 **Booking Engine** – Farmers can book or lend their equipment when not in use.
- 🔒 **Secure Authentication** – JWT-based secure login.
- 📊 **Analytics Ready** – Logs for usage, demand patterns, and peak season planning.

---

## 🏗️ Tech Stack & Frameworks

| Layer            | Tech Used                |
|------------------|--------------------------|
| Language         | JavaScript (Node.js)     |
| Backend Framework| Express.js               |
| Database         | MongoDB + Mongoose ORM   |
| Dev Tools        | Nodemon, Git, GitHub     |
| Hosting (Planned)| Render / Railway / Heroku|
| Package Manager  | npm                      |
| Version Control  | Git                      |
| Platform         | GitHub                   |

---

## 🚀 How to Run Locally

### 🧱 Prerequisites

- Node.js (v18+ recommended)
- MongoDB Atlas or Local Mongo
- Git installed

### 🔧 Setup Steps

```bash
# Clone the repository
git clone https://github.com/your-username/mittimobil.git
cd mittimobil

# Install dependencies
npm install

# Add your MongoDB URI in a .env file
touch .env
# Inside .env
MONGO_URI=your_mongodb_connection_string

# Run the server
npm run dev
