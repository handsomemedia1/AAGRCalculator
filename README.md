# 📊 AAGR Calculator

A React-based tool for calculating Average Annual Growth Rates (AAGR) across key environmental and economic indicators. Designed for use with U.S. greenhouse gas commentary and World Bank data.

## 🚀 Features

- Input start and end values for CO₂ emissions, population, GDP per capita, and carbon intensity
- Automatically calculates AAGR for each variable across selected periods
- Highlights special cases like excluding recession or pandemic years
- Responsive and intuitive UI built with Tailwind CSS
- Helpful instructions and notes for accurate data entry

## 📐 AAGR Formula



\[
\text{AAGR} = \left( \left( \frac{\text{End Value}}{\text{Start Value}} \right)^{\frac{1}{\text{Years}}} - 1 \right) \times 100
\]



## 📦 Installation

```bash
git clone https://github.com/your-username/aagr-calculator.git
cd aagr-calculator
npm install
npm start
