# 🎓 LearnSphere

### Learn Skills. Build Your Future.

LearnSphere is a premium, modern, frontend-only online learning platform designed to help learners discover useful **free online courses** from trusted learning platforms.

The project provides an easy way to explore courses, search and filter learning resources, view detailed course information, and access external course platforms.

---

## 🌐 Project Overview

LearnSphere is developed as a collaborative **Git and GitHub project** by a team of four members.

The platform focuses on providing a simple and professional learning experience where users can:

- 📚 Browse free online courses
- 🔍 Search for courses
- 🗂️ Filter courses by category
- 📊 Filter courses by difficulty
- 📖 View detailed course information
- 🔗 Access external learning platforms
- 🤖 Interact with LearnBot
- 🌙 Switch between Light and Dark modes
- 📱 Use the platform on desktop, tablet, and mobile devices

---

## ✨ Features

### 🏠 Homepage

- Modern and responsive landing page
- Attractive hero section
- Featured courses
- Learning statistics
- Why LearnSphere section
- Motivational learning quotes
- LearnBot promotion section
- Call-to-action sections

---

### 📚 Course Catalogue

- Dynamic course loading using `fetch()`
- Course data loaded from `courses.json`
- Responsive course grid
- Dynamic course cards
- Case-insensitive course search
- Category filtering
- Difficulty filtering
- Combined search and filtering
- No-results handling

Users can search courses using:

- Course title
- Category
- Platform
- Course description

---

### 🔎 Filters

Courses can be filtered by:

#### Category

- Programming
- Web Development
- Data Science
- Artificial Intelligence
- Database
- Developer Tools
- Cybersecurity

#### Difficulty

- All
- Beginner
- Intermediate

All filters work together with the search functionality.

---

### 📖 Course Details

LearnSphere uses a single dynamic course details page.

Example:

```text
course-details.html?course=python