# Finance Tracker Logic (JS-based)

This project solves the issue of manual financial reporting by automating tax calculations and data aggregation directly in the UI.

## 🚀 The Goal
I wanted to build a form that doesn't just collect data, but processes it. The main challenge was to handle floating-point math in JavaScript and ensure the UI stays responsive while processing large tables.

## 🛠 Features
- **Live VAT Calculation:** Automatically calculates 20% tax for each row using a JS listener.
- **Data Aggregation:** Groups raw input into categories (e.g., Travel, Software, Logistics) for reporting.
- **UI Interaction:** Real-time total sum updates using `toLocaleString` for professional currency formatting.
- **Robustness:** Includes data sanitization (handling `NaN` and empty strings) to prevent calculation errors.

## 💻 Tech Highlights
- **Language:** ES6 JavaScript
- **Platform:** Plumsail Automation
- **Key Methods:** `parseFloat()`, `reduce()`, `forEach()`, Event Listeners.

## 📖 What I learned
While building this, I realized that data types are crucial. I had to implement strict parsing to avoid string concatenation issues (like `100 + 50 = 10050`). I also optimized the grouping logic to make it ready for Chart.js integration.
