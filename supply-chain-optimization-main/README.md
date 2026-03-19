## Supply Chain Optimisation with Python 👷
This project implements a supply chain network optimization model using Python to minimize total transportation cost while satisfying supply and demand constraints. Linear Programming is used to determine the most efficient distribution strategy across the network
<p align="center">
  <a href="https://www.samirsaci.com/supply-chain-optimization-with-python/"><img align="center" src="https://www.samirsaci.com/content/images/size/w1200/2025/12/temp-49.png"></a>
</p>

### Cost Parameters and Demand Data
In this we will present a simple methodology using Linear Programming for Supply Chain Optimisation, considering
- Fixed production costs of your facilities ($/Month)
- Variable production costs per unit produced ($/Unit)
- Shipping costs ($)
- Customer’s demand (Units)


## Code
In this repository, you will find all the code used to explain the concepts presented in the article.

### Files
- `Supply Chain Optimization.ipynb` - Jupyter notebook with step-by-step analysis
- `supply_chain_optimization.py` - Standalone Python script

### Getting Started
This project uses [uv](https://docs.astral.sh/uv/) for dependency management.

```bash
# Install dependencies
uv sync

# Run the Python script
uv run python supply_chain_optimization.py

# Or launch Jupyter notebook
uv run jupyter notebook
```

### Dependencies
- pandas
- pulp
- openpyxl
- jupyter
