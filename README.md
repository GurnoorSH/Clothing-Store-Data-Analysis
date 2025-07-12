# Clothing Store Data Analysis

A comprehensive exploratory data analysis (EDA) of Vrinda Store’s sales and customer data to uncover trends, customer demographics, and channel performance, and to provide actionable insights for business growth.

---

## 📋 Table of Contents

1. [Project Overview](#project-overview)  
2. [Dataset](#dataset)  
3. [Environment Setup](#environment-setup)  
4. [Usage](#usage)  
5. [Analysis Highlights](#analysis-highlights)  
6. [Project Structure](#project-structure)  
7. [Technologies & Libraries](#technologies--libraries)  
8. [Contributing](#contributing)  
9. [License](#license)  
10. [Contact](#contact)  

---

## 🔍 Project Overview

This project analyzes one year of Vrinda Store’s order-level data (2022), covering:

- **Sales Performance:** Total revenue, monthly trends, state-level breakdown  
- **Customer Demographics:** Age groups, gender distribution  
- **Order Attributes:** Channel usage, order statuses, product categories, sizes  
- **Geographic Insights:** Top shipping cities and states  

The goal is to identify strengths, weaknesses, and opportunities for targeted marketing and operational improvements.

---

## 📂 Dataset

- **Source file:** `data/Vrinda Store Data Analysis 1.xlsx`  
- **Key columns:**
  - `Order ID`, `Date`, `Status`, `Channel`
  - `Gender`, `Age`, `Age Group`
  - `SKU`, `Category`, `Size`, `Qty`, `Amount`
  - `ship-city`, `ship-state`, `B2B`
- **Precomputed pivot sheets:**  
  - Orders vs Sales  
  - Men vs Women  
  - Order Status distribution  
  - State-wise sales  
  - Age vs Gender  
  - Order Channel share  

---

## ⚙️ Environment Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/<your-username>/vrinda-store-data-analysis.git
   cd vrinda-store-data-analysis
