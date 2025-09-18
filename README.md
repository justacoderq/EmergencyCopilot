# Emergency Copilot — Prototype

**Disclaimer:** This is a **simulated demo** of a financial assistance tool for presentation and testing purposes. No real loans or financial decisions are being made.  

---

## Overview

**Emergency Copilot** is a prototype that simulates how a bank (like Wells Fargo) could assist customers in emergency financial situations. It demonstrates:  

- Step-by-step guidance for applying for an emergency loan (chatbot flow).  
- Manual loan application form (for testing input).  
- Advisor verification simulation.  
- Repayment dashboard with visual repayment schedule.  
- Predictive alerts based on income, expenses, and potential emergencies.  

The prototype is entirely **client-side** and uses **simulated data** for demonstration.  

---

## How to Use the Prototype

1. **Open the Prototype**  
   Open `index.html` in a modern web browser (Chrome, Edge, Firefox).  

2. **Sign In (Demo Mode)**  
   Click the **Sign in (Demo)** button in the top-right to simulate a user login.  

3. **Home Tab**  
   The Home tab lets you choose between:  
   - **Chatbot Guide** — interact with a Copilot chatbot that asks questions about your category and emergency, then calculates a suggested loan.  
   - **Manual Apply** — fill out a form to request a loan manually (optional for testing).  

4. **Chatbot Flow**  
   - Answer the questions step by step.  
   - After answering, the system simulates sending your request for verification.  
   - **Advisor approval message** appears.  
   - The **Repayment Dashboard** automatically shows **5 seconds after approval**.  

5. **Manual Apply Flow**  
   - Select category and emergency, optionally input requested amount.  
   - Click **Calculate & Request**.  
   - The loan shows as pending verification; you can simulate advisor approval to see the dashboard.  

6. **Repayment Dashboard**  
   - Shows the loan amount, duration, and a visual repayment chart.  
   - Use **Mark as Repaid** to simulate completing the loan and see recommendations for staying prepared.  

7. **Predictive Alerts Tab**  
   - Click **Run Simulation** to see a demo of how AI/ML could predict upcoming financial emergencies.  
   - Alerts include cash flow gaps, income instability, and high expense months.  
   - Interactive buttons simulate actions you could take.  

---

## Notes for the User

- All data is simulated; numbers, charts, and alerts are for **demo purposes only**.  
- You can interact with both chatbot and manual apply flows to see different scenarios.  
- Local storage is used to **save demo loans**, so refreshing the page will keep your loan history.  
- Buttons labeled “Simulate” or “Demo” **do not affect real accounts**.  

---

## Key Files

- `index.html` — Main prototype interface.  
- Embedded `<script>` — All logic for chatbot, manual apply, loan calculations, dashboard, and predictive alerts.  
- CSS is in the `<style>` tag in the `<head>` for simplicity.  

---

## Recommended Browser Features

- Modern browsers (Chrome, Edge, Firefox) with JavaScript enabled.  
- **Canvas support** for repayment chart visualization.  
- Local storage access for loan history simulation.  

---

## Credits

- Prototype designed for **demo and presentation purposes**.  
- Simulated Copilot chatbot and predictive logic created by Prachi Aswani.  
