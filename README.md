# LSPort

# Required Packages
| Name         | Pacakage                                                                                                                        | File                                             |                           
| ------------ | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| Pandas       | ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)                    | All Files|
| Matplotlib   | ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)        | LSPort.py
| PuLP         |                                                                                                                                 | LSPair.py

# Background
Long Short Pair Backtesting Tool (still in development)
see testing.ipynb for example. Built on top of [LSPair](https://github.com/diegodalvarez/LSPair), future development will also develop streamlit-based downstream web-facing GUI like [LSPair Streamlit Repo](https://github.com/diegodalvarez/LSPairStreamlit) [LSPair Streamlit link](https://diegodalvarez-lspairstreamlit-streamlit-frontend-f78dmo.streamlit.app/)

# Sample Test Runs
## Long AAPL short AMZN benchmark QQQ rolling 120 day beta daily rebalance
Weighting and Beta Matching
![image](https://github.com/diegodalvarez/LSPort/assets/48641554/712db1c4-0d9e-4259-8273-c8a52648737f)
Portfolio Beta exposure, comparative returns and portfolio cumulative returns
![image](https://github.com/diegodalvarez/LSPort/assets/48641554/e9c93ad1-a536-4dc6-aa58-15ffa7c74669)

## Long Fallen Angels and Short HYG hedging beta via TLT (US 10y Treasury ETF)
The code's beta optimization may not be solvable within 100% fully funded (no leverage) positions and thus there is a 10% mininum holding per each name. We can see that happen when we run this pair. 
![image](https://github.com/diegodalvarez/LSPort/assets/48641554/97d3b581-8110-433c-bd3d-32a2c71944e5)
![image](https://github.com/diegodalvarez/LSPort/assets/48641554/30022929-3adf-47e0-a93d-71203b856609)

Also this idea comes from some of my other work on Long Fallen Angels. You can find the repo [here](https://github.com/diegodalvarez/FallenAngelRiskPremia)
