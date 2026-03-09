
# 🛰️ UCI TSP Visualizer: "Soar Into Data" Datathon Winner

**🏆 Awarded 1st Place at the 2024 Melissa Data Challenge (150+ Participants)**

The **UCI TSP Visualizer** is a route optimization engine designed to solve "The Traveling Student Problem." Built for the "Soar Into Data" Datathon, it helps UC Irvine students—especially those new to the area—minimize travel time and latency when navigating local errands, grocery runs, and daily commutes.

## 🚀 Key Features

*   **📌 Static Route Optimization:** Processes a fixed list of essential Irvine locations, calculates the most efficient round-trip sequence, and visualizes the path.
*   **🧭 Dynamic Route Planning:** Allows real-time user input for current locations and custom errands, dynamically re-calculating the optimal route order.
*   **📍 Melissa Data Integration:** Leverages professional-grade APIs to verify addresses, retrieve precise geocoordinates, and classify locations (Residential vs. Business).
*   **🧠 TSP Algorithmic Logic:** Implements a Traveling Salesperson Problem (TSP) algorithm in Python to ensure the mathematically shortest path.

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Backend/Logic:** Python (TSP Optimization Logic)
- **APIs:** 
    - **Melissa Global Address API:** For geocoding and address validation.
    - **Melissa Address Key (MAK):** For data uniqueness and accuracy.

## 🧠 How It Works

1.  **Input:** Users provide a list of addresses via the web interface.
2.  **Validation:** The system passes inputs through the **Melissa API** to clean data and obtain exact latitude/longitude coordinates.
3.  **Optimization:** A **Python-based TSP algorithm** calculates the shortest path that visits every location exactly once and returns to the origin (UCI).
4.  **Visualization:** The optimized sequence is rendered on an interactive map for the user.

## 📂 Project Structure

```bash
├── frontend/
│   ├── css/
│   │   └── style.css      # Custom UI styling
│   ├── static.html        # Interface for fixed route tool
│   ├── dynamic.html       # Interface for real-time route tool
│   └── team.html          # Project contributors
├── index.html             # Main landing page
└── backend/               # Python logic for TSP and API integration
```

## 🏆 Hackathon Achievement

Developed within 48 hours, this project secured **1st Place** among **150+ participants**. The judges recognized the tool for:
- Seamlessly integrating **Melissa Data** intelligence into a functional product.
- High technical execution in combining algorithmic complexity with a responsive UI.
- Addressing a real-world "Last Mile" logistics problem for the student community.
  
---
*Developed by UCI Students for the Melissa Data Challenge 2025.*
