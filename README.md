# Financial Health Checker and Retirement Planner

This is a Jupyter notebook that will offer clients a small financial planner for a possible emergency fund based on their current portfolio. And the members will be able to use this tool to forecast a reasonably effective retirement plan based on their current portfolio. We will show this to them with a 10 year and 30 year possible outcome of their portfolio based on different weighting strategies between their stocks and bonds.
---

## Technologies

This project utilizes a lot of different add ons, please make sure you have all these and they are up to date:

* [JupyterLab 3.3.2](https://jupyter.org/) - For the notebook creation and running of the code.

* [pandas 1.4.2](https://github.com/pandas-dev/pandas/blob/main/README.md) - For reading the csv files and other operations.

* [Matplotlib 4.0](https://matplotlib.org/) - For plotting graphs and charts that appear below the code.

* [requests v2.28.0](https://pypi.org/project/requests/) - For making API calls.

* [python-dotenv v0.20.0](https://github.com/theskumar/python-dotenv) - For reading .env files.

* [alpaca-trade-api v2.3.0](https://github.com/alpacahq/alpaca-trade-api-python) - For making api calls with Alpca and using their SDK.

Be sure you can import these local tools in to your Jupyter Lab as they will be necessary for the program.

```python

    import json
    
    import os
  
```

You will also need the following python file: MCForecastTools.py.
We have provided it with the notebook, so please download it as well.

```python

    from MCForecastTools import MCSimulation
    
```

We will be utilizing the above to run the Monte Carlo simulation portion of the project.
This will be necessary for the retirement forecasting.

---

## Installation Guide

All of the above will need to be installed. You will also need to provide your own API Keys for Alpca to access their network.

Please save these items in a .env file with the headings of:

ALPACA_API_KEY = "*YOUR ALPACA API KEY HERE!*"

ALPACA_SECRET_KEY = "*YOUR ALPACA SECRET KEY HERE!*"

Have this file located in the same location as this notebook.

Again, please make sure you have **MCForecastTools.py** on your system and that it is in the same file location as the notebook, as well.

---

## Usage

To access the financial planner notebook, please begin by typing jupyter lab in your terminal. 

```python
jupyter lab
```

Next, find the folder with the notebook(financial_planning_tools.ipynb) and double click it to open it up in a new launcher. Then, begin running through each section of the application to get the appropriate data.

Once in the notebook it will take you through a step-by-step process as it Collects the Data, Prepares the Data, and Analyzes the Data.
You will be granted visualizations along the way to help better see and understand the data.

We do believe everything is thoroughly explained in the notebook, but please let us know if you have any further questions.

---
## Contributors

### Matthew Stream
m.stream3663@gmail.com

[LinkedIn](https://www.linkedin.com/in/matthew-stream-mba-215634102/)

---

## License

MIT