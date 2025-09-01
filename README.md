# Sustainable Supply Chain Optimization – GreenGlow Cosmetics  

## 📌 Project Overview  
This project develops a prescriptive analytics model for **GreenGlow Cosmetics**, a fictional multinational skincare company, to optimize its global supply chain. Implemented as part of the MSc Business Analytics program at **University College Cork**, the model balances **cost, emissions, and customer satisfaction** across multiple suppliers, plants, and demand regions.  

The model was built using **Mixed Integer Linear Programming (MILP)** in **Pyomo**, with scenario and sensitivity analyses to evaluate trade-offs between efficiency and sustainability.  

---

## ✨ Key Features  
- Designed and implemented a **MILP optimization model** in Python using Pyomo.  
- Optimized procurement, production, and distribution across **4 plants and 6 demand regions**.  
- Incorporated **supplier capacity, demand fluctuations, and carbon emission caps**.  
- Conducted **scenario-based and sensitivity analyses** for different supply-demand conditions.  
- Delivered recommendations for **supplier prioritization, plant utilization, and sustainable logistics**.  

---

## 🛠 Tech Stack  
- **Language:** Python  
- **Libraries:** Pyomo, NumPy, Pandas, Matplotlib, Seaborn, Folium  
- **Solver:** CBC  

---

## 📊 Results  
- **Base Case** revealed ~93% unmet demand due to supplier limitations.  
- **Tighter emission caps** reduced CO₂ but significantly increased unmet demand.  
- **Customer satisfaction priority scenarios** increased demand fulfillment but raised costs.  
- **Scenario and sensitivity analysis** showed trade-offs between **cost efficiency and sustainability goals**.  

---

## 🚀 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/nikhil26vaddadi/green-glow-supply-chain-optimization.git
   cd green-glow-supply-chain-optimization
   
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt

3. Run the notebook in Jupyter/Colab:  
   ```bash
   jupyter notebook "Prescriptive_Analytics.ipynb"
