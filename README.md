# Sustainable You 🌿🐸

**Sustainable You** is an interactive, mobile-responsive web application designed to help users track and improve their daily environmental habits. By gamifying eco-friendly choices, users can log daily activities, calculate their carbon footprint, reduce food and water waste, and compete on a live global leaderboard—all while advancing the **United Nations Sustainable Development Goals (SDGs)**.

---

## 🚀 Features & SDG Alignment

Sustainable You breaks down sustainability into actionable, everyday habits mapped directly to specific UN Sustainable Development Goals:

### 1. 🧊 Fridge Rescue
* **SDG Goal 2: Zero Hunger 🌾**
* **SDG Goal 12: Responsible Consumption & Production ♻️**
* **Description:** Track items in your fridge alongside their expiration dates. Log items as eaten or rescued to earn bonus points, or log wasted food to see the impact. Features a smart recipe suggestion engine to help cook aging produce before it spoils.

### 2. 💧 Drop Counter
* **SDG Goal 6: Clean Water & Sanitation 💧**
* **Description:** Monitor and record daily household water consumption with quick-add actions (showers, dishes, laundry, etc.). Compete against the global recommended daily limit ($\le 100\text{ Litres/day}$) and visualize usage history over a 7-day rolling window.

### 3. 🍽️ Carbon Plate
* **SDG Goal 12: Responsible Consumption & Production ♻️**
* **SDG Goal 13: Climate Action 🌍**
* **Description:** Interactive meal builder that calculates total estimated $\text{CO}_2$ equivalent emissions ($\text{kg CO}_2\text{e}$) based on food choices. Provides instant, low-carbon food swap recommendations (e.g., swapping beef for lentils or tofu) to minimize diet-related emissions.

### 4. 🌊 Ocean Cleanup Sorter
* **SDG Goal 14: Life Below Water 🐟**
* **Description:** An arcade-style interactive game where players drag falling waste items into proper disposal bins (Recycle, Compost, Trash) before they pollute the ocean. Earn points based on accuracy and speed.

### 5. 📅 Habit Calendar & 🏆 Global Leaderboard
* **Progress Tracking:** Interactive monthly calendar highlighting days with active habits logged.
* **Real-time Synchronization:** Built on Firebase Authentication and Firestore to save user scores, track daily streaks, and update the live global leaderboard across all devices seamlessly.

---

## 🛠️ Tech Stack

* **Frontend:** Plain HTML5, CSS3 (Mobile-first responsive design with dark mode support), Custom Vanilla JavaScript (ES6+).
* **Backend & Authentication:** Firebase Web SDK (v10 / v13 compatibility) providing Firebase Auth (Email/Password) and Cloud Firestore.
* **Hosting:** GitHub Pages / Static Web Hosting.

---

## 🔒 Security & Privacy

This public repository contains only public client-side configuration code. API security is enforced via cloud protections:
* **HTTP Referrer Restrictions:** Google Cloud API key restricted strictly to authorized website domains.
* **Firestore Security Rules:** Server-level authentication checks preventing unauthorized reading or overwriting of user documents.

---

## 💻 Getting Started Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/the-sustainable-you.git](https://github.com/your-username/the-sustainable-you.git)