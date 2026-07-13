# OIBSIP — Oasis Infobyte Internship (Web Development & Designing)

This repository contains all the tasks I completed during the **Oasis Infobyte Summer Internship Program (OIBSIP)** in the Web Development & Designing domain. The work is organised into three levels, moving from static web pages built with plain HTML/CSS up to a complete full-stack application.

**Author:** Katta Charan Raj

## Repository Structure

```
OIBSIP/
├── KATTACHARANRAJ_LEVEL_1/   # Level 1 — HTML & CSS fundamentals
│   ├── KATTA_CHARAN_RAJ_TASK_1/   # Landing page
│   ├── KATTA_CHARAN_RAJ_TASK_2/   # Personal portfolio
│   └── KATTA_CHARAN_RAJ_TASK_3/   # Temperature converter
├── KATTACHARANRAJ_LEVEL_2/   # Level 2 — JavaScript projects
│   ├── KATTA_CHARAN_RAJ_TASK_1/   # Calculator
│   ├── KATTA_CHARAN_RAJ_TASK_2/   # Tribute page
│   ├── KATTA_CHARAN_RAJ_TASK_3/   # To-do app
│   └── KATTA_CHARAN_RAJ_TASK_4/   # Login authentication
└── KATTACHARANRAJ_LEVEL_3/   # Level 3 — Full-stack pizza delivery app
    ├── client/                    # React (Vite) frontend
    └── server/                    # Node.js / Express / MongoDB backend
```

## Level 1 — HTML & CSS

| Task | Project | Description | Tech |
|------|---------|-------------|------|
| 1 | **Landing Page** | A simple, styled welcome/landing web page. | HTML, CSS |
| 2 | **Personal Portfolio** | A portfolio website showcasing personal details, skills, and projects. | HTML, CSS |
| 3 | **Temperature Converter** | Converts temperatures between Celsius, Fahrenheit, and Kelvin with input validation. | HTML, CSS, JavaScript |

**How to run:** open the `index.html` file of any task directly in a web browser — no setup needed.

## Level 2 — JavaScript

| Task | Project | Description | Tech |
|------|---------|-------------|------|
| 1 | **Calculator** | An interactive calculator supporting basic arithmetic operations. | HTML, CSS, JavaScript |
| 2 | **Tribute Page** | A tribute page dedicated to Spider-Man, with imagery and styled content. | HTML, CSS |
| 3 | **To-Do App** | A to-do list app where tasks can be added, completed, and deleted. | HTML, CSS, JavaScript |
| 4 | **Login Authentication** | A client-side login/registration flow demonstrating basic authentication logic. | HTML, CSS, JavaScript |

**How to run:** open the `index.html` file of any task directly in a web browser — no setup needed.

## Level 3 — Pizza Delivery Application (Full Stack)

A complete pizza ordering system built with the **MERN-style stack**: a React (Vite) frontend and a Node.js/Express backend with MongoDB.

### Features

- **User accounts** — registration, login (JWT-based), email verification, and forgot/reset password flows.
- **Custom pizza builder** — choose base, sauce, cheese, and veggies to build your own pizza.
- **Ordering & checkout** — place orders and track their status in *My Orders*.
- **Admin dashboard** — manage inventory (bases, sauces, cheeses, veggies) and update order statuses.
- **Email notifications** — verification and password-reset links sent via Nodemailer (or printed to the server console if email isn't configured).
- **Auto-seeding** — on first run the server creates an admin account, a test user, and starter inventory automatically.

### Tech Stack

- **Frontend:** React 18, React Router, Axios, Vite
- **Backend:** Node.js, Express, Mongoose (MongoDB), JWT, bcryptjs, Nodemailer

### How to Run

Prerequisites: **Node.js** and **MongoDB** (local install or MongoDB Atlas).

1. **Backend** (first terminal):

   ```bash
   cd KATTACHARANRAJ_LEVEL_3/server
   npm install
   npm run dev
   ```

   Configuration lives in `server/.env` (see `.env.example` for all options, including the MongoDB connection string and optional email credentials).

2. **Frontend** (second terminal):

   ```bash
   cd KATTACHARANRAJ_LEVEL_3/client
   npm install
   npm run dev
   ```

   Then open the printed URL (usually `http://localhost:5173`).

3. **Default logins:**

   | Role | Email | Password |
   |------|-------|----------|
   | Admin | `admin@pizza.com` | `admin123` |
   | Test user | `test@gmail.com` | `test123` |

   You can also register a new account and verify it via the emailed (or console-printed) link.

See [KATTACHARANRAJ_LEVEL_3/README.md](KATTACHARANRAJ_LEVEL_3/README.md) for more details.

## About OIBSIP

The Oasis Infobyte Summer Internship Program is a virtual internship that assigns hands-on projects across levels of increasing difficulty, helping participants build practical skills in web development — from static pages to full-stack applications.
