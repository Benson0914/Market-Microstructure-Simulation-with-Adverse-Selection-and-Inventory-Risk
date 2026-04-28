# Simulation of Adverse Selection in Market Making
I simulate how liquidity providers interact with informed and uninformed order flow. 
keywords: (order flow, price formation, liquidity provision, adverse selection , inventory risk)

Market Microstructure Simulation of Market Making and Adverse Selection

# **📌 Motivation**

This project simulates a simplified financial market where a market maker interacts with informed (toxic) and uninformed order flow.

The goal is to study how spread capture competes with inventory risk and adverse selection.

# **⚙️ Model Components**

**1. Price Process**

- Geometric / arithmetic Brownian motion

**2. Order Flow**

- Poisson arrivals
- toxic flow (informed traders)
- persistent flow (retail behavior)

**3. Market Maker**

- quotes bid/ask
- inventory skew
- spread adjustment

# **💰 PnL Decomposition**

PnL = Spread PnL

- Adverse Selection

+ Inventory Exposure

# **📊 Key Insight**

Even with positive spread capture, the strategy can be unprofitable when inventory risk dominates under volatile or toxic environments.

# **🔬 Experiment Results**

========================== PnL Breakdown ==========================

- Spread PnL: 18.9299
- Adverse Selection: -2.5179
- Inventory Exposure: 0.4741
- Total PnL: 16.8861

# **🚀 Extensions**

- toxicity estimation
- optimal quoting (Avellaneda-Stoikov)
- dynamic spread adjustment
- risk constraints
