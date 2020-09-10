# What
Using Matplotlib to plot S&P 500 historical data. Data is obtained from https://financialmodelingprep.com/developer/docs/.

![Demo](https://github.com/quad-coders/financial-modeling/blob/master/demo1.png)
![Demo](https://github.com/quad-coders/financial-modeling/blob/master/demo2.png)

# Environment
Python 3.7.3
Library:
- Pandas 1.1.1
- Matplotlib 3.3.1

# Setup
1. Install Python https://www.python.org/downloads/.
2. Clone this repo.
3. In the root of the repo, create Python virtual environment, read about virtual environment here https://www.geeksforgeeks.org/python-virtual-environment/.
You can follow the instruction on the link, or simply run command below:
`python3 -m venv .venv`
4. Activate virtual environment, this is assuming the name of the virtual environment is `.venv`.
Mac: `source .venv/bin/activate`
Windows: `.venv/scripts/activate`
5. Install requirements. If you don't have pip, follow this: https://evansdianga.com/install-pip-osx/.
`pip3 install -r requirements.txt`
6. The scripts are in Jupyter Notebook format, you can install Jupyter Notebok (https://jupyter.org/install) or use your favorite editor (Conda, VS Code, etc).

# The Code
1. There are 2 scripts:
    - Single-year is a script to plot single year of S&P 500 historical data.
    - Multi-year is a script to plot multiple years of S&P 500 historical data into single chart to compare its pattern.

2. To convert this to Python scripts, simply change the file extension to `.py`.
3. Data from 2015 - 2019 are included, both as individual year or 5 years span.