# 🔧 Network Resilience Analysis: Final Year Project

This project evaluates the resilience of synthetic random graphs under various attack strategies, using simulations and graph-theoretic metrics.

---

## 🧠 Objective

To explore how random networks respond to:
- Random node removals
- Targeted attacks based on degree and centrality
And to propose strategies for strengthening connectivity.

---

## 🔍 Key Features

- Simulated Erdős–Rényi (ER) graphs with increasing node counts
- Modeled random vs. targeted attacks
- Evaluated:
  - Size of the largest connected component (GCC)
  - Average path length
  - Clustering coefficients
- Proposed a local triangle-closing rewiring strategy to improve resilience

---

## 🛠️ Tools & Technologies

- MATLAB (Simulations and Plotting)
- Graph Theory Metrics
- PDF Report (attached in `docs/`)

---

## 📊 Key Results

- Targeted attacks on high-degree nodes fragmented the network fastest  
- Rewiring edges based on local clustering increased robustness  
- Performance metrics plotted across multiple scenarios

---

## 📁 Repository Structure

📁 /docs

└── CityU_FYP_Network_Resilience_Report.pdf

📁 /code

└── resilience_simulation.m # Sample simulation script

📁 /visuals/graphs

└── fragmentation_plots.png

---

## 👤 Author

**Gerald Chan Kin Lok**  
BEng in Electrical Engineering — City University of Hong Kong  
📫 Contact: culerty516@gmail.com
