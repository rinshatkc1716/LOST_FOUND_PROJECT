<p align="center"><img src="./img.png" alt="Project Banner" width="100%"></p>

# UniSolve 🎯

## Basic Details

**Team Name:** TOM & jerry

**Team Members:**  
Rinsha TKC – MAMO College 


**Hosted Project Link:** https://rinshatkc1716.github.io/LOST_FOUND_PROJECT/

---

## Project Description

UniSolve is a multi-module campus utility web platform that helps students solve everyday campus problems through a single unified portal. It provides tools for Lost & Found reporting, Study Help requests, Skill Exchange, Opportunity sharing, Lunch coordination, and Live Campus event tracking.

The platform is built as a lightweight frontend web app using HTML, CSS, and JavaScript with browser localStorage-based persistence and optional cloud database integration setup.

---

## The Problem & Solution

### ❌ The Problem
Students face multiple small but frequent campus challenges — lost items, finding study help, discovering opportunities, skill collaboration, and knowing what’s happening live on campus. These are usually scattered across chats, posters, and informal groups.

### ✅ The Solution
UniSolve brings all these needs into a single structured web platform with dedicated modules. Students can log in and post or browse structured entries across categories, making campus collaboration faster, searchable, and organized.

---

# Technical Details

## Technologies Used

**Frontend**
- HTML5
- CSS3
- Vanilla JavaScript

**Storage**
- Browser localStorage (primary persistence)
- Appwrite JS SDK (configured in Lost & Found module — ready for backend extension)

**Tools & Libraries**
- Appwrite CDN SDK
- Responsive card-based UI
- Dark mode with persistent preference

**Architecture Type**
- Multi-page frontend web application
- Client-side authentication
- Client-side data persistence

---

# Features

## 🔑 Authentication System
- User registration and login
- Credentials stored in localStorage
- Route protection for all modules
- Session flag (`loggedIn`) check on every protected page

## 🔍 Lost & Found Module
- Report lost or found items
- Search filter by item name
- Delete entries
- Type-based styling (Lost / Found)
- Appwrite database client configured for future backend storage

## 📚 Study Help Board
- Post academic help requests
- Subject + description + contact capture
- Structured help cards display

## 🤝 Skill Exchange
- Offer or request skills
- Skill + contact listing
- Type-colored cards (Offer / Request)

## 🚀 Opportunities Board
- Post internships, hackathons, workshops
- Category-based styling
- Title + description + link/contact

## 🍱 LunchLink
- Lunch need/offer matching
- Pickup location support
- Stored posts with delete option

## 🔴 Live Campus Programs
- Add live campus events
- Start & end time tracking
- Auto status:
  - LIVE NOW
  - Starting Soon
  - Ended

## 🌙 Dark Mode
- Toggle across pages
- Preference persisted in localStorage

---

# video link : 
https://s57-hzfi.freeconvert.com/task/698fec632732b0f98da00e1d/Untitled%20video%20-%20Made%20with%20Clipchamp.mp4
## Installation

This is a static frontend project — no package manager required.

```bash
# Clone the repository
git clone [INSERT HERE]

# Enter project folder
cd [project-folder]
