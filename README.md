# Portfolio Builder Project

This project demonstrates how ETF-based investment portfolios can be tailored to different investor risk profiles using Python, Jupyter Notebooks, and simple data visualization techniques.

## Project Overview

The goal is to build a beginner-friendly tool that:
- Accepts a user-defined **risk profile** (`Conservative`, `Balanced`, or `Aggressive`)
- Outputs a sample ETF allocation strategy based on that profile
- Saves the allocation as a CSV file for further analysis

This serves as a great starting point for anyone exploring **personal finance**, **portfolio modeling**, or **data analytics** in Python.

## Tech Stack

- **Python 3.13**
- **Jupyter Notebooks**
- **pandas** for data wrangling
- **matplotlib** for visualizations
- **Git & GitHub** for version control

## Folder Structure


##  How to Run the Project

1. **Clone this repository**
2. Open `01_risk_profile.ipynb` in Jupyter
3. Change the `risk_profile` variable to one of:
   - `'Conservative'`
   - `'Balanced'`
   - `'Aggressive'`
4. Run the notebook to view the allocation table
5. A CSV file will be saved automatically to the `output/` folder

##  Sample Output (Balanced)

| ETF Name                  | % Allocation |
|---------------------------|--------------|
| SPY (S&P 500)             | 40%          |
| VTI (US Total Market)     | 30%          |
| BND (Total Bond)          | 20%          |
| GLD (Gold)                | 10%          |

##  Future Ideas

- Allow custom portfolio weights or ETF selections  
- Integrate historical return/risk data for comparisons  
- Build a simple dashboard using **Streamlit** or **Power BI**

## Author

**Jaikhush Thakkar**  
Double Major in Applied Statistics & Economics | Penn State University  
[GitHub](https://github.com/YOUR_USERNAME) • [LinkedIn](https://www.linkedin.com/in/YOUR_USERNAME)
