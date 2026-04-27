# RunwayAI

A simple web app to calculate how long your startup cash will last.

---

## Features

- Runway calculation (months & days)
- Net burn auto-calculation  
- Multi-currency support:
  - USD ($)
  - EUR (€)
  - INR (₹)
  - GBP (£)
  - JPY (¥)
- Financial status:
  - 🟢 Safe (≥ 6 months)
  - 🟡 Warning (3–6 months)
  - 🔴 Danger (< 3 months)
- Cash burn chart (Chart.js)
- Dark / Light mode
- Shareable results

---

## Tech Stack

- HTML  
- CSS  
- JavaScript  
- Chart.js  

---

## Usage

1. Open `RunwayCalcu.html`  
2. Enter:
   - Total cash  
   - Monthly burn rate  
   - (Optional) Revenue  
3. Click **Calculate Runway →**

---

## Formula

```text
Runway = Total Cash ÷ (Burn − Revenue)
