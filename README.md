 📌 Overview
Managing multiple job applications across different companies can quickly become difficult. Important details such as application dates, current status, deadlines, interview stages, and job links can easily get scattered across notes and spreadsheets.

Job Tracker Dashboard provides a centralized workspace where users can record, manage, search, filter, and analyze their job applications.

The application is built as a client-side Single Page Application (SPA) using React and Vite, with application data persisted using the browser's Local Storage.

No backend or database is required.

🎯 The application allows users to:
Add and manage job applications
Track application progress
Update application statuses
Record application dates and deadlines
Store job links and notes
Search applications quickly
Filter applications by status
Sort applications
Navigate through applications using pagination
Analyze job-search activity through interactive charts
Persist application data across browser refreshes
✨ Key Features
📋 Application Management
Create and manage job applications from a centralized dashboard.

➕ Add new applications
✏️ Edit existing applications
🗑️ Delete applications
🏢 Track company names
💼 Track job roles
🔗 Store application/job links
📝 Add notes and additional information
📅 Record application dates
⏰ Set application deadlines
🔎 Search & Filtering
Quickly find relevant applications using smart controls.

Search by company name
Search by job role
Filter by application status
Combine search and filtering for faster navigation
Supported statuses:

🟦 Applied
🟨 Interview
🟩 Offer
🟥 Rejected
↕️ Sorting
Applications can be organized using multiple sorting options:

Newest First
Oldest First
Company A–Z
This makes it easier to prioritize recent applications and locate companies quickly.

📄 Pagination
The application uses client-side pagination to keep the dashboard clean and manageable.

10 applications per page
Previous/Next navigation
Automatically adapts to filtered results
📊 Analytics Dashboard
The application includes a dedicated analytics dashboard that transforms application data into useful visual insights.

📈 Interactive Visualizations
Built using Recharts.

🥧 Status Distribution
A pie chart showing the proportion of applications across different statuses.

📊 Status Comparison
A bar chart comparing the number of applications in each stage.

📈 Monthly Application Trend
A line chart showing application activity over time.

🏢 Top Companies
Highlights companies receiving the highest number of applications.

🎯 Offer Success Rate
Calculates the percentage of applications that resulted in an offer.

💾 Data Persistence
The application uses the browser's Local Storage API for client-side data persistence.

This means:

Application data survives browser refreshes
No backend server is required
No external database is required
The application can work entirely offline after loading
User data remains stored within the browser
Data Flow
User Action
     ↓
React State
     ↓
Application Data
     ↓
Local Storage
     ↓
Persisted Browser Data
When the application loads, stored data is retrieved from Local Storage and restored into the application state.

Project Structure
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

🧠 Core Concepts Demonstrated
This project demonstrates practical frontend development concepts including:

React
Functional components
React Hooks
useState
useEffect
Component composition
Props
Controlled forms
Conditional rendering
Data Management
CRUD operations
State management
Array manipulation
Data transformation
Local Storage integration
Persistent client-side state
