# Crypto Crash Early Warning



A data-driven framework to identify **high-risk crypto market regimes** using drawdowns and a composite risk index built from volume, volatility,and price behavior.



This project focuses on **risk detection**, not price prediction or trading.



## Overview



Instead of asking *“When will price fall?”*, this project asks:



**Can market stress be detected objectively before and during crashes?**



Daily Bitcoin price and volume data is analyzed to:

- Define crashes using drawdowns

- Study early-warning risk signals

- Combine signals into a composite risk index





## Methodology



- **Crash Definition:**  

&nbsp; Crashes are defined using peak-to-trough drawdowns (not daily returns)



- **Risk Signals Used:**  

&nbsp; - Volume stress  

&nbsp; - Volatility expansion  

&nbsp; - Drawdown momentum  



- **Composite Risk Index:**  

&nbsp; Signals are normalized and combined into a single risk score

&nbsp; to represent overall market stress.



The system is intentionally **conservative and confirmation-based**.





## Project Structure



- **notebooks** – analysis notebooks (01 → 04)
  
- **data** – BTC daily OHLCV data
  
- **notes** – conceptual and design notes






## Key Takeaway



Crypto crashes emerge from the accumulation of stress across volume, volatility, and price dynamics.

Simple, interpretable signals can reliably identify high-risk market regimes without complex models.




