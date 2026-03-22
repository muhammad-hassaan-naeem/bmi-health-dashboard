# BMI Health Dashboard

**Author:** Muhammad Hassaan Naeem  
**Role:** Lab Engineer @ SCAT | ML Researcher  
**LinkedIn:** [muhammad-hassaan-naeem](https://www.linkedin.com/in/muhammad-hassaan-naeem-b51610354/)  
**Live Demo:** Open `bmi-calculator.html` in any browser — no installation needed
\n**Website Link:** https://muhammad-hassaan-naeem.github.io/bmi-health-dashboard/bmi-calculator.html

---

## What is this?

A fully interactive, single-file BMI and health metrics calculator built with HTML, CSS, and JavaScript. No frameworks, no dependencies, no internet required after download — just open the file and use it.

---

## Features

| Metric | Description |
|---|---|
| **BMI** | Body Mass Index with animated radial gauge |
| **Category** | Underweight / Normal / Overweight / Obese I / Obese II+ |
| **Ideal Weight** | Healthy weight range for your height (BMI 18.5–24.9) |
| **BMR** | Basal Metabolic Rate — Mifflin–St Jeor equation |
| **TDEE** | Total Daily Energy Expenditure by activity level |
| **Body Surface Area** | Mosteller formula (m²) |
| **Lean Body Mass** | Boer formula |
| **Body Fat %** | Estimated from lean mass |
| **Total Body Water** | Watson formula (litres) |
| **Ponderal Index** | kg/m³ — scales better than BMI for tall/short individuals |
| **Frame Size** | Small / Medium / Large based on wrist measurement |
| **Plasma Volume** | Nadler formula (mL) |
| **Water Intake** | Daily hydration target (30 mL/kg) |
| **Protein Target** | Minimum daily protein range based on lean mass |
| **Fibre Target** | Daily fibre based on caloric needs |
| **Macro Split** | Protein / Carbs / Fat with animated donut chart |
| **Goal Calories** | Weight loss / Maintenance / Muscle gain targets |
| **Population Chart** | Where your BMI sits vs global population |

---

## Inputs

- Height (cm or ft/in)
- Weight (kg or lbs)
- Age
- Biological sex
- Activity level
- Goal (lose / maintain / gain)
- Waist circumference *(optional)*
- Hip circumference *(optional)*
- Neck circumference *(optional)*
- Wrist circumference *(optional)*

Supports both **Metric** and **Imperial** units.

---

## How to use

**Option 1 — Download and open:**
1. Download `bmi-calculator.html`
2. Double-click to open in any browser
3. Enter your details — results update instantly

**Option 2 — Clone the repo:**
```bash
git clone https://github.com/muhammad-hassaan-naeem/bmi-health-dashboard
cd bmi-health-dashboard
# Open bmi-calculator.html in your browser
```

---

## Screenshots

> Dark-themed dashboard with animated gauges, donut chart, metric tiles, and BMI reference table.

---

## Formulas Used

| Metric | Formula |
|---|---|
| BMI | weight(kg) / height(m)² |
| BMR (male) | 10W + 6.25H − 5A + 5 |
| BMR (female) | 10W + 6.25H − 5A − 161 |
| BSA | √(height × weight / 3600) |
| LBM (male) | 0.407W + 0.267H − 19.2 |
| LBM (female) | 0.252W + 0.473H − 48.3 |
| TBW (male) | 2.447 − 0.09156A + 0.1074H + 0.3362W |
| TBW (female) | −2.097 + 0.1069H + 0.2466W |
| Ponderal Index | weight / height(m)³ |
| Plasma Vol (male) | (0.3669H³ + 0.03219W + 0.6041) × 1000 |

---

## Tech Stack

- Pure **HTML5**
- Pure **CSS3** — dark theme, animations, responsive layout
- Pure **JavaScript** — all calculations, no libraries

Single file. Zero dependencies. Works offline.

---

## Medical Disclaimer

This tool is for **informational purposes only** and does not constitute medical advice. Consult a qualified healthcare professional before making any health or dietary decisions.

---

## License

MIT License — free to use, modify, and share with attribution.
