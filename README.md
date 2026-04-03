# Rebadgeonboard1
# RebadgeOnboard | GLITCH THE SYSTEM
### SANKALP – DELVE 2026 Case Competition

**RebadgeOnboard** is a comprehensive, AI-powered onboarding platform built for **SuppOrg Pvt. Ltd.** It is designed to manage the high-stakes lifecycle of employee rebadging and HR transfers following business acquisitions. 

The system focuses on eliminating "onboarding chaos" by synchronizing HR Transition Managers, Line Managers, and Rebadging Employees in a single, secure source of truth.

---

## 🚀 Key Features

### 1. Role-Based Experience (4 Distinct Flows)
- **Rebadging Employee:** Guided checklists, document uploads, and offer acknowledgement.
- **HR Transition Manager:** Bulk data uploads, term comparisons, and automated reminders.
- **Hiring/Line Manager:** Productivity tracking and team assimilation tools.
- **Customer/Incumbent HR:** Secure data sharing for due diligence.

### 2. Interactive "RebadgeBot" (AI Assistant)
- A context-aware chatbot prototype that answers common onboarding queries (Document verification, Offer letters, IT access, and Day-1 Readiness).

### 3. Real-Time Readiness Meter
- A visual data representation of onboarding progress (e.g., tracking a 150-employee scenario) that calculates Day-1 readiness based on document and task completion.

### 4. Technical Prototype Features
- **Functional Auth System:** A demo-ready Sign-In/Sign-Up system utilizing `localStorage` to persist user roles and sessions.
- **Interactive Tutorial:** A toggleable step-by-step guide showing the journey from both Employee and HR perspectives.
- **Glassmorphism UI:** Modern, high-performance interface built with Tailwind CSS and custom CSS keyframe animations (Grid Drift, Glitch Effects).

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Custom Animations/Keyframes)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (CDN)
- **Logic:** Vanilla JavaScript (ES6+)
- **Storage:** Web Storage API (`localStorage`) for session management and user simulation.
- **Icons/Visuals:** HeroIcons (SVG), Custom CSS Glassmorphism, and Neon-UI design language.

---

## 📂 Project Structure

- `index.html`: The core application containing the UI, Styles, and Logic.
- **Internal Modules:**
    - `readinessMeter()`: Handles the SVG dash-array animation.
    - `authSystem`: Manages local user registration and role-based access.
    - `RebadgeBot`: Logic for the support chatbot and viewer assistant.
    - `tutorialEngine`: Dynamic rendering of the 6-step onboarding timeline.

---

## 📖 How to Use

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/rebadge-onboard.git](https://github.com/your-username/rebadge-onboard.git)
