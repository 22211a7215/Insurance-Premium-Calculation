# Insurance-Premium-Calculation
# 💼 Dynamic Insurance Premium Calculator

A fully client-side web application that dynamically calculates personalized insurance premiums using modern HTML, CSS, and JavaScript. Built with a clean architecture and responsive UI, this project simulates real-world risk evaluation and pricing based on user input and simulated market conditions.

---

## 🚀 Tech Stack

### 🖥️ Frontend Technologies
- **HTML5**: Semantic, structured markup
- **CSS3**:
  - Responsive layouts using **Flexbox** and **CSS Grid**
  - Custom properties (CSS variables)
  - Gradients, transitions, and animations
- **Vanilla JavaScript (ES6+)**:
  - Modular ES6 Classes
  - Template literals, arrow functions
  - Real-time DOM manipulation
  - File download via **Blob API**

---

## 🧠 Architecture Pattern

- **Object-Oriented Programming (OOP)** using JavaScript classes
- **Component-Based Design**: Each logical unit (input, calculator, renderer) is isolated
- **Client-Side Only**: No backend required — works entirely in the browser

---

## ⚙️ Workflow

### 1. 🔽 Data Input Phase
- User provides:
  - Personal Info (age, gender, location, occupation, smoking status)
  - Policy Info (coverage amount, term)
- Real-time validation and UX feedback

### 2. 🔄 Calculation Phase
- Risk score based on user input
- Simulated market conditions adjust the premium
- Custom rules applied (term multipliers, occupation risks)

### 3. 📊 Results Display Phase
- Color-coded **Risk Indicator Bar**
- Detailed **Premium Breakdown**
- Simulated **Market Trends Chart**
- Downloadable **Quote Document**

---

## 🧮 Configuration Constants

| Factor                     | Value                         |
|---------------------------|-------------------------------|
| Base Premium Rate         | `0.8%` of coverage per year   |
| Risk Score Range          | Multiplier: `0.5` to `2.5`    |
| Term Multiplier           | `<10 yrs`: `1.1`, `>20 yrs`: `0.95` |
| Quote Validity            | 30 days                       |

---

## 📦 Dataset & Templates

- **Hardcoded demo dataset** for quick calculation
- **Benefits & Terms** are predefined templates
- Multiplier logic for benefit-based coverage

---

## 🌟 Key Features

- ⚡ **Real-Time Calculations**: Instant updates on input
- 🧱 **Risk Visualization**: Color-coded indicator bar
- 📈 **Market Simulation**: Inflation/volatility factor adjustments
- 📄 **Quote Generation**: Download-ready PDF/HTML quote
- 📱 **Responsive Design**: Fully mobile-optimized

---

## 📷 Screenshots

![Form Screenshot](screenshots/form.png)
![Result Screenshot](screenshots/result.png)

---

## 📁 Project Structure


