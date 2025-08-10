# DO — Personal To-Do PWA

A lightweight, offline-first **Progressive Web App** for managing personal tasks on iPhone (or any modern browser). Built with **HTML + CSS + JavaScript**, deployed via GitHub Pages, and installable to your Home Screen with no App Store or iOS development required.  
> *Vibe coded with ChatGPT* ✨

---

## 🌟 Why I Built My Own To-Do App

Most to-do apps in the market are **too heavy**, cluttered with extra features I never use, and often come with **advertisements** or complicated menus. I just wanted:

- **Simple, clean functions** for my daily workflow  
- A **checkmark system** that, when ticked, automatically updates the due date for repeating items (e.g., utility payments)  
- No distractions, no bloat — just the essentials  
- Fast and lightweight enough to **install directly on my iPhone** without dealing with App Store rules or iOS development tools

I couldn’t find an easy, minimal app that did exactly this… so I built my own.

---

## ✨ Features

- **Add / edit / delete** tasks with due date, priority, and tags  
- **Repeat schedules**, including *Bi-weekly*  
- **Offline support** via Service Worker — works without network  
- **Local data persistence** in IndexedDB (private to the device/browser)  
- **Sorting** by due date, priority, or smart  
- **Tag filtering** for focused task views  
- **Floating Add Task button** optimized for iPhone standalone mode  
- **Yellow DO branding** and PWA icon

---

## 🛠 Technologies Used

- **HTML5** for app structure  
- **CSS3** for styling (mobile-first, yellow theme, responsive layout)  
- **JavaScript (ES6)** for logic and UI updates  
- **IndexedDB** for local task storage  
- **Service Worker** for offline caching and installability  
- **Web App Manifest** for Home Screen install & branding  
- **GitHub Pages** for hosting

---

## 🚀 Setup & Configuration

1. **Clone this repo**  
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
