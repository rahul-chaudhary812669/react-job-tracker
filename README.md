 ## 📌 Overview

Managing multiple job applications across different companies can quickly become difficult. Important details such as application dates, current status, deadlines, interview stages, and job links can easily get scattered across notes and spreadsheets.

**Job Tracker Dashboard** provides a centralized workspace where users can record, manage, search, filter, and analyze their job applications.

The application is built as a **client-side Single Page Application (SPA)** using **React and Vite**, with application data persisted using the browser's **Local Storage**.

No backend or database is required.

### 🎯 The application allows users to:

- Add and manage job applications
- Track application progress
- Update application statuses
- Record application dates and deadlines
- Store job links and notes
- Search applications quickly
- Filter applications by status
- Sort applications
- Navigate through applications using pagination
- Analyze job-search activity through interactive charts
- Persist application data across browser refreshes

---

## ✨ Key Features

### 📋 Application Management

Create and manage job applications from a centralized dashboard.

- ➕ Add new applications
- ✏️ Edit existing applications
- 🗑️ Delete applications
- 🏢 Track company names
- 💼 Track job roles
- 🔗 Store application/job links
- 📝 Add notes and additional information
- 📅 Record application dates
- ⏰ Set application deadlines

---

### 🔎 Search & Filtering

Quickly find relevant applications using smart controls.

- Search by **company name**
- Search by **job role**
- Filter by application status
- Combine search and filtering for faster navigation

Supported statuses:

- 🟦 Applied
- 🟨 Interview
- 🟩 Offer
- 🟥 Rejected

---
job-tracker/
│
├── public/
│   └── _redirects
│
├── src/
│   │
│   ├── components/
│   │   ├── JobForm.jsx
│   │   ├── JobItem.jsx
│   │   ├── JobList.jsx
│   │   ├── Navbar.jsx
│   │   └── Stats.jsx
│   │
│   ├── pages/
│   │   └── Analytics.jsx
│   │
│   ├── styles/
│   │   └── app.css
│   │
│   ├── App.jsx
│   └── main.jsx
│
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── README.md
└── vite.config.js


---

## 🧠 Core Concepts Demonstrated

This project demonstrates practical frontend development concepts including:

### React

- Functional components
- React Hooks
- `useState`
- `useEffect`
- Component composition
- Props
- Controlled forms
- Conditional rendering

### Data Management

- CRUD operations
- State management
- Array manipulation
- Data transformation
- Local Storage integration
- Persistent client-side state

### User Interaction

- Search
- Filtering
- Sorting
- Pagination
- Form validation
- Dynamic UI updates
