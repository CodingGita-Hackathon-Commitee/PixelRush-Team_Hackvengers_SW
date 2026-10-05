# SurplusLink ♻️ | PixelRush 2026 Hackathon Submission

**A Real-Time Surplus Food Coordination Platform**
*Submitted for the PixelRush 2026 CodingGita Hackathon (October 5-6, 2026)*[cite: 1, 2]

---

## 📌 Project Overview
Restaurants, cafeterias, hostels, bakeries, and institutional kitchens frequently prepare more food than is consumed[cite: 2]. Often, good food expires simply because local NGOs and community members are unaware of its availability in time[cite: 2]. 

**SurplusLink** is a time-sensitive coordination engine designed to solve this gap. Moving beyond traditional "food donation," our platform connects verified local recipients with food providers to ensure surplus inventory is claimed, reserved, and picked up before it becomes unusable[cite: 2].

## 🚀 The Solution & Key Features
Our submission encompasses a complete UI/UX blueprint and frontend implementation tracking the lifecycle of surplus food from discovery to handover. 

### Core Workflow (7 Required Screens)
1. **The Glass Matrix Landing Page (Custom Add-on):** A premium, glassmorphism-inspired entry point establishing the platform's time-sensitive mission and routing users to provider or recipient workflows.
2. **Nearby Surplus Feed:** A live, geographically sorted feed of available surplus (e.g., Bakery leftovers, Hostel dinner)[cite: 3]. It features dynamic urgency color-coding so users instantly understand how much time is left to rescue the food[cite: 3].
3. **Create Surplus Listing:** A frictionless, rapid-entry form for kitchen staff to list food name, quantity, expiry time, pickup windows, and critical safety details (allergens, veg/non-veg)[cite: 3].
4. **Listing Details:** A comprehensive view of the selected listing, featuring remaining quantity, an expiry countdown timer, distance/directions, and a clear "Request" action[cite: 3].
5. **Recipient Verification & Request:** A secure gateway allowing verified recipients (NGOs, community groups) to request specific quantities and assign pickup personnel[cite: 3].
6. **Reservation & Digital Ticket:** A digital holding state featuring a pickup QR code, reservation countdown, and a critical "Release" function to prevent waste if the recipient cannot make the pickup window[cite: 3].
7. **Pickup Confirmation:** A dual-scan handover screen to close the loop, confirm food safety conditions, and log feedback[cite: 4].
8. **Provider Analytics:** A CSR (Corporate Social Responsibility) dashboard tracking food listed vs. rescued, meals saved over time, and top recipients[cite: 4].

---

## 🎨 Design & Development Architecture

### Phase 1: Figma Design (The Blueprint)
Following the event guidelines, the entire experience was designed in Figma prior to writing code[cite: 5]. 
* **Responsive Thinking:** The core 7-screen flow was fully mapped across three distinct device breakpoints: **Laptop, Tablet, and Mobile**[cite: 5]. 
* **Interactive Prototype:** A fully connected, interactive prototype was built to demonstrate the seamless user journey from the surplus feed to the final analytics dashboard[cite: 6]. 

### Phase 2: Frontend Implementation (The Execution)
The design was meticulously translated into code using strictly **HTML and CSS**[cite: 6]. 
* **Design-to-Code Consistency:** High priority was placed on matching the visual hierarchy, typography, custom spacing, and component structure established in the Figma blueprint[cite: 6].
* **Hackathon Compliance Note:** In strict adherence to the hackathon's "HTML/CSS Requirement," responsive CSS (media queries) was purposefully omitted from the code[cite: 7]. The codebase focuses entirely on an accurate structural and stylistic translation of the fixed design layout[cite: 7, 9]. 

---

## 🛠️ Tech Stack
* **Design & Prototyping:** Figma
* **Markup:** HTML5 (Semantic Structure)
* **Styling:** CSS3 (BEM Methodology, Custom CSS Variables)
* **Development Workflow:** Claude Code (Agentic UI refinement)

---

## ⚙️ How to Run Locally
1. Clone the repository to your local machine.
2. Ensure you have a modern web browser installed (Chrome, Safari, Firefox).
3. Open `index.html` in your browser to start the experience from the Glass Matrix Landing Page.
4. Navigate through the application using the integrated UI buttons to experience the full food-rescue workflow.
