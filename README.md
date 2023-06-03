# LS Port
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
