# ⚡ AuraX'26

### Innovation Ignites the Future.

🚀 A modern full-stack digital platform designed to transform the way participants discover, explore, register, and engage with technical college festivals.

---

## 🌟 Overview

**AuraX'26** is a comprehensive digital platform for technical college festivals, bringing event discovery, registration, personalized recommendations, schedules, participant networking, mentor support, preparation resources, and digital event passes together in one interactive experience.

From discovering an event to registering, preparing, managing schedules, connecting with mentors, and accessing a digital festival pass, everything is organized within a single platform.

---

# 🔥 What AuraX'26 Does

## 🚀 Personalized Onboarding

Participants begin with a guided onboarding experience.

Users can provide:

- Name
- College / Institution
- Areas of interest

Their interests can be used to personalize event recommendations and their festival experience.

---

## 🎯 Smart Event Explorer

Participants can explore the complete festival lineup through a centralized event discovery experience.

Features include:

- Search events
- Filter events by category
- View event descriptions
- Check event timings
- View venues
- Check team requirements
- View prize information
- Explore required technologies
- Check seat availability
- Register for events
- Unregister from events
- Bookmark events
- Discover personalized recommendations

---

## ⚠️ Smart Schedule Clash Detection

AuraX'26 checks registered events for overlapping schedules.

Participants are notified when multiple registered events have conflicting timings, helping them organize their festival schedule more effectively.

---

## 📅 Interactive Event Timeline

The platform provides an interactive visual timeline for the complete festival schedule.

Participants can view:

- Event start time
- Event end time
- Event duration
- Venue
- Event progress
- Upcoming events

Interactive event cards provide additional event information.

---

## 📊 Personalized Festival Dashboard

The dashboard provides participants with a centralized overview of their festival activities.

It includes:

- 📋 Registered events
- ⭐ Bookmarked events
- 📅 Festival events
- 🏆 Prize information
- 👤 Participant profile
- Event timings
- Event venues
- Registration details

Participants can manage their festival activities directly from the dashboard.

---

## 📚 Preparation Resource Hub

Participants can access curated resources to prepare for different technical events.

Resources can include:

- 📖 Competitive Programming Guides
- 🐙 GitHub Starter Templates
- 🧠 Machine Learning Resources
- 🎨 UI/UX Design Resources
- 🤖 Robotics & IoT Resources
- ⚡ Full-Stack Development Resources

Resources can be explored based on participant interests and event requirements.

---

## 🧑‍🏫 Mentor Support System

AuraX'26 provides a mentor-support system for participants who need guidance.

Mentors can be categorized into domains such as:

- AI & Machine Learning
- Full Stack Development
- UI/UX Design
- Robotics & IoT
- Competitive Programming
- Cloud & DevOps

Participants can:

- Explore available mentors
- View mentor expertise
- Check availability
- Select a mentor
- Submit a help request
- Describe their problem or requirement

---

## 🔎 Smart FAQ Center

The platform includes a searchable FAQ section for common festival-related questions.

Participants can find information related to:

- Registration
- Venues
- Event schedules
- Event fees
- Food
- Certificates
- Event requirements
- General festival information

---

## 👥 Participant Networking

AuraX'26 provides a participant discovery experience to encourage networking.

Participant profiles can include:

- Name
- College / Institution
- Skills
- Interests
- Participating events
- Availability / online status

Users can also create and customize their own participant profile.

---

## 🎟️ Digital Festival Pass

Registered participants can access a personalized digital festival pass.

The pass can contain:

- Participant name
- College / Institution
- Pass ID
- Registered events
- QR-based identification
- Pass validity

The digital pass can also be printed or saved for event-day access.

---

## ⏱️ Event Countdown

The platform includes an interactive countdown for the upcoming festival.

The countdown displays:

- Days
- Hours
- Minutes
- Seconds

---

# ✨ User Experience

AuraX'26 is designed with a futuristic technical-event aesthetic.

The interface focuses on:

- ⚡ Dark futuristic UI
- ✨ Neon-inspired visual elements
- 🪟 Glass-style cards
- 🌌 Animated backgrounds
- 💫 Glow effects
- 🎯 Interactive event cards
- 🖱️ Smooth hover interactions
- ✨ Cursor effects
- 📱 Responsive layouts
- 🎨 Strong visual hierarchy

The overall design is intended to make the platform feel like a **digital festival experience** rather than a conventional event website.

---

# 🧠 Technology Stack

## Frontend

- React
- Vite
- JavaScript / JSX
- React Router
- Axios
- CSS
- Responsive Web Design

## Backend

- Python
- FastAPI
- Pydantic
- Uvicorn
- Motor

## Database

- MongoDB

## Authentication & Security

- JWT-based authentication
- Password hashing with bcrypt
- Environment-based configuration

## Development Tools

- Git
- GitHub
- ESLint

---

# 🏗️ System Architecture

AuraX'26 follows a full-stack architecture where the frontend communicates with the backend through REST APIs.

```text
                 ┌─────────────────────────┐
                 │      AuraX'26 UI        │
                 │     React + Vite        │
                 └────────────┬────────────┘
                              │
                              │ REST API
                              ▼
                 ┌─────────────────────────┐
                 │     FastAPI Backend     │
                 │        Python           │
                 └────────────┬────────────┘
                              │
                              ▼
                 ┌─────────────────────────┐
                 │        MongoDB          │
                 │                         │
                 │ Users • Events •        │
                 │ Mentors • Participants  │
                 └─────────────────────────┘
```

---

# 🔌 Backend API

The backend provides REST API routes for major platform functionality:

```text
/api/users
/api/events
/api/mentors
/api/faqs
/api/participants
```

Health monitoring:

```text
/health
```

FastAPI interactive API documentation:

```text
http://127.0.0.1:8000/docs
```

---

# 📁 Project Structure

```text
AuraX-26/
│
├── backend/
│   └── app/
│       ├── core/
│       │   └── config.py
│       │
│       ├── models/
│       │   ├── event.py
│       │   ├── mentor.py
│       │   └── user.py
│       │
│       ├── routes/
│       │   ├── events.py
│       │   ├── faqs.py
│       │   ├── mentors.py
│       │   ├── participants.py
│       │   └── users.py
│       │
│       ├── schemas/
│       │   ├── event.py
│       │   └── user.py
│       │
│       ├── database.py
│       └── main.py
│
├── frontend/
│   ├── public/
│   │
│   └── src/
│       ├── assets/
│       ├── components/
│       │   ├── About.jsx
│       │   ├── ContactSection.jsx
│       │   ├── Dashboard.jsx
│       │   ├── DigitalPass.jsx
│       │   ├── EventsExplorer.jsx
│       │   ├── Hero.jsx
│       │   ├── Navbar.jsx
│       │   ├── OnboardingModal.jsx
│       │   ├── ParticipantProfiles.jsx
│       │   ├── ResourceHub.jsx
│       │   ├── Schedule.jsx
│       │   └── SparkleCursor.jsx
│       │
│       ├── data/
│       │   └── events.js
│       │
│       ├── App.jsx
│       ├── App.css
│       ├── index.css
│       └── main.jsx
│
├── .gitignore
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone <your-repository-url>
cd AuraX-26-main
```

---

## 2️⃣ Backend Setup

Navigate to the backend:

```bash
cd backend
```

Create a Python virtual environment:

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### macOS / Linux

```bash
source venv/bin/activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Configure Environment Variables

Create a `.env` file inside the backend directory.

Example:

```env
MONGO_URI=mongodb://localhost:27017
DB_NAME=aurax26
SECRET_KEY=your-secret-key
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=60
```

For production deployment, use secure credentials and environment variables.

---

## 4️⃣ Start the Backend

From the backend directory:

```bash
uvicorn app.main:app --reload
```

The backend will run at:

```text
http://127.0.0.1:8000
```

API documentation:

```text
http://127.0.0.1:8000/docs
```

---

## 5️⃣ Frontend Setup

Open a new terminal:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The frontend will normally be available at:

```text
http://localhost:5173
```

---

# 🧪 Available Commands

### Start Development Server

```bash
npm run dev
```

### Create Production Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Run Linter

```bash
npm run lint
```

---

# 🗄️ Database

AuraX'26 uses **MongoDB** for storing application data.

The backend communicates with MongoDB using the asynchronous **Motor** driver.

Example local configuration:

```text
MongoDB URI: mongodb://localhost:27017
Database: aurax26
```

---

# 🔐 Security Considerations

For production deployment, the following should be configured securely:

- Use environment variables for sensitive values
- Replace development secret keys
- Secure the MongoDB connection
- Configure appropriate CORS policies
- Enable HTTPS
- Validate user input
- Protect authenticated API routes
- Implement proper authorization
- Avoid exposing sensitive participant information

---

# 🚀 Future Enhancements

- 🔐 Complete participant authentication and authorization
- 📱 Dedicated mobile application
- 🔔 Push notifications for event updates
- 📧 Automated registration and reminder emails
- 📊 Advanced organizer analytics
- 🏆 Live event leaderboards
- 📜 Automated certificate generation
- 📍 Interactive campus navigation
- 💬 Real-time participant and mentor communication
- 📡 Live event status updates
- 🧑‍💼 Advanced organizer/admin dashboard
- ☁️ Cloud-based deployment
- 📈 Real-time participation analytics
- 🤖 More advanced personalized event recommendations

---

# 🏆 Project Highlights

✔ Full-stack technical festival platform  
✔ Modern event discovery experience  
✔ Personalized participant onboarding  
✔ Smart event recommendations  
✔ Event registration and bookmarking  
✔ Schedule clash detection  
✔ Interactive event timeline  
✔ Personalized festival dashboard  
✔ Preparation resource hub  
✔ Mentor support system  
✔ Smart FAQ search  
✔ Participant networking  
✔ Digital festival pass  
✔ Interactive countdown  
✔ Futuristic and responsive UI  
✔ Scalable frontend-backend architecture  
✔ MongoDB-powered data management  

---

# 📌 Conclusion

**AuraX'26** is a complete digital platform designed to make technical college festivals more interactive, organized, and engaging.

It brings event discovery, registration, personalized recommendations, schedule management, preparation resources, mentor support, participant networking, FAQs, and digital festival passes together into one connected experience.

With its modern user interface, full-stack architecture, and participant-focused features, AuraX'26 provides a complete digital experience for managing and participating in technical festivals.

### ⚡ Innovation Ignites the Future.
