# Hayat Alghamdi – Interactive Portfolio Website (Assignment 3)


This project is the **final advanced version** of my personal portfolio, extending Assignment 1 and Assignment 2.  
It now includes **API integration, complex JavaScript logic, advanced state management, performance optimization, and documented AI usage** as required in Assignment 3.

---

# Project Overview

This website serves as my personal Computer Science portfolio, showcasing my skills, projects, and contact form in a fully responsive, interactive, and high-performance design.

Assignment 3 focused on transforming the portfolio into a **dynamic web application** with:

- Real API data  
- Complex JS filtering and animations  
- State persistence using LocalStorage  
- Contact form with validation and async sending  
- High performance (Lighthouse 100% desktop, 98–100% mobile)  
- Strong documentation & AI-usage logs

---

# New Features Added in Assignment 3

### 1. **Weather API Integration**
- Uses browser **geolocation**; falls back to reverse geocoding or default city **Dhahran**.
- Fetches live weather using:  
  `https://goweather.herokuapp.com/weather/{city}`
- Includes **loading state**, **error UI**, and **weather display** in the greeting bar.

### 2. **Project Filtering System**
- Filter projects by programming language:
  - Java, Python, Web Design, All
- Smooth staggered animations  
- Prevents overlapping operations (`isFiltering` flag)

### 3. **Welcome-Back Message (State Management)**
- Saves user’s name in LocalStorage.
- If user visits again → greeting changes to **“Welcome back”**.
- State restored automatically on reload.

### 4. **Advanced Contact Form**
- Inline field validation  
- Email regex  
- Minimum length constraints  
- Async send via Formspree (with loading button + success & error messages)

### 5. **Performance Enhancements**
- `defer` JS loading  
- Optimized DOM ops  
- Removal of unused functions  
- Lighthouse Results:  
  - **100% Desktop**  
  - **98–100% Mobile**

### 6. **Fully Updated Documentation**
- Technical documentation  
- AI-usage report  
- README  
All redesigned specifically for Assignment 3.

---

# Folder Structure

```
Assignment-3/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── assets/
│   ├── images/
│   └── icons/
├── docs/
│   ├── ai-usage-report.md
│   └── technical-documentation.md
└── README.md
```

---

# How to Run the Project

### Requirements
- Modern browser (Chrome, Firefox, Edge, Safari)
- Internet connection (for weather API + form submission)

### Steps
1. Download or clone the repo.
2. Open **index.html** in any browser.
3. All features will work immediately (no build tools required).

---

# Live Demo

https://vuir.github.io/Assignment-3/


---

# AI Usage
This project uses AI tools responsibly.  
See detailed documentation in: **docs/ai-usage-report.md**


