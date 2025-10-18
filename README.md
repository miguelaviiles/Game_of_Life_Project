<div align="center">



**Conway's Game of Life: Advanced Simulation & Analysis**  
*Master's Project - Team Implementation*

</div>

## 🎮 Introduction to the Game of Life

**Developed by:**  
[Miguel Avilés](https://github.com/yourusername) 
[Sebastian Waruszynski](https://github.com/sebastianwaruszynski)  
[Martina Cassina](https://github.com/martinacassina)  
[Fredy Dairy](https://github.com/fredydairy)  

This repository implements Conway's **Game of Life** with advanced features: **Gaussian probability initialization**, **pattern detection & evolution tracking**, **vectorized NumPy optimization**, and **statistical analysis** across multiple simulations.

---

## 📜 Core Rules

| Rule | Description | Outcome |
|------|-------------|---------|
| **1** | Live cell with <2 or >3 neighbors | **Dies** (under/overpopulation) |
| **2** | Live cell with 2-3 neighbors | **Survives** |
| **3** | Dead cell with exactly 3 neighbors | **Born** (reproduction) |

---

## 🌊 Probability Distribution Grid Generation

### Initial Parameters
- **m = 3** Gaussians
- **σ = 5** (standard deviation)

### Mathematical Formulation
For cell `(i,j)` and Gaussian center `(r_k, c_k)`:


**Activation:** Cell is alive if `random(0,1) < P_norm(i,j)`

**Result:** Non-uniform, clustered initial patterns!



git clone https://github.com/yourusername/GameofLife_Final_Version.git
cd GameofLife_Final_Version

pip install -r requirements.txt  # numpy, matplotlib

python main.py  # Run simulation
python analysis.py  # Generate plots


