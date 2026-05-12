# Visualizing Causes of Death in the Crimean War: A Coxcomb Chart

## Background

Florence Nightingale was a British nurse and statistician who played a crucial role in improving healthcare during the Crimean War (1853–1856). While working in military hospitals, she discovered that most soldier deaths were caused not by battle wounds, but by preventable diseases linked to poor sanitation.

To communicate this to government officials, she invented the **coxcomb chart** (also called a polar area chart) — a powerful visualization that made the data impossible to ignore. Her work led to major reforms in military healthcare and sanitation.

This project recreates Nightingale's famous diagram using Python.

---

## Project Overview

Using two monthly datasets covering the periods **April 1854 – March 1855** and **April 1855 – March 1856**, this project:

- Loads and merges both datasets
- Cleans and explores the data structure
- Recreates Nightingale's two circular coxcomb plots side by side, showing deaths by:
  - 🔵 **Disease** (preventable/zymotic causes)
  - 🔴 **Wounds** (battle injuries)
  - ⬜ **Other causes**

---

## Key Finding

Disease was overwhelmingly the leading cause of soldier deaths in both periods — far exceeding deaths from wounds or other causes. While disease-related deaths declined slightly in the second period (possibly reflecting early sanitation improvements), they remained dramatically higher than combat fatalities throughout the war.

---

## Files in This Repository

| File | Description |
|------|-------------|
| `Nightingale_project.ipynb` | Jupyter Notebook with all code, visualizations, and written analysis |
| `raw_night_1854_1855.xlsx` | Monthly death data for April 1854 – March 1855 |
| `raw_night_1855_1856.xlsx` | Monthly death data for April 1855 – March 1856 |

---

## Tools & Libraries

- Python 3
- `pandas` — data loading and manipulation
- `numpy` — numerical calculations
- `matplotlib` — coxcomb/polar chart visualization

---

## How to Run

1. Clone this repository or download the files
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib openpyxl
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Nightingale_project.ipynb
   ```
4. Run all cells from top to bottom

> **Note:** Make sure both `.xlsx` dataset files are in the **same folder** as the notebook before running.

---

## Author

**Mercy Inameti Etim**  
Student ID: SCA/APC3/DS/147
