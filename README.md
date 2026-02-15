# **Stock Trading Decision Support System using Fuzzy Logic**

## Project Overview

This **Decision Support System (DSS)** implements a **Mamdani Fuzzy Inference System** to simulate objective trading recommendations **(Buy, Hold or Sell)** for the Indonesian banking sector. The system analyzes the correlation between stock **Closing Prices** and **Trading Volume** using a mathematical framework to handle market ambiguity.

The analysis covers the "Big Four" banks:

- **BBCA** (PT Bank Central Asia Tbk)
- **BBRI** (PT Bank Rakyat Indonesia Tbk)
- **BMRI** (PT Bank Mandiri Tbk)
- **BBNI** (PT Bank Negara Indonesia Tbk)

## Project Context

This project was developed as a **Freelance Commission**. The goal was to build a consistent simulation tool to validate trading strategies using historical data from late 2014 to 2024.

## The Problem & Solution

- **Market Uncertainty**: Stock movements often fall into "gray areas" that rigid logic cannot capture. Fuzzy Logic allows for smoother decision transitions.
- **Decision Bias**: This tool provides a systematic approach to trading, minimizing emotional bias by relying on a predefined fuzzy rule base.

## Tech Stack

- **Language**: Python
- **Platform**: Google Colab
- **Libraries**:
  - **Data Processing:** Pandas & NumPy
  - **Fuzzy Logic:** Scikit-Fuzzy _(skfuzzy)_
  - **Visualization:** Matplotlib
- **Data Sources**: Historical stock price datasets (2014-2015)

## Key Features

- **Triangular Membership Functions**: Categorizes `prices` and `volume` into Low, Medium, and High levels using the `trimf` method for precise fuzzification.
- **Automated Decision Simulation**: Iterates through historical datasets to generate Buy/Hold/Sell signals based on 3 core fuzzy rules.
- **Data Integrity Validation**: Includes logic to handle invalid inputs (e.g., zero or negative prices/volume) and missing data columns.
- **Visual Analytics**: Generates comprehensive visual reports, including line charts for price trends, bar charts for decision distribution, and pie charts for percentage analysis.

## How to Run

1. **Clone Repository**: Download or clone this repository to your machine.
2. **Install Dependency**: Run `!pip install scikit-fuzzy` in your Colab environment.
3. **Upload Dataset**: Upload the `.csv` files from the `datasets/` folder into your Google Colab environment or Google Drive path.
4. **Run Notebook**: Open `Fuzzy_Trading.ipynb` located in the `notebooks/` directory and run the cells.
5. **Review Analysis**: View the generated decision charts and percentage distributions at the bottom of the notebook.

## Repository Structure

- `notebooks/`: Contains the core logic file `Fuzzy Trading.ipynb`.
- `datasets/`: Historical `.csv` datasets for BBCA, BBRI, BMRI, and BBNI.
- `docs/`: Technical documentation and analysis report.

## My Role

**Independent Developer & Data Researcher**

- Architected the Mamdani Fuzzy Inference System for stock trading.
- Performed data cleaning and preprocessing on historical banking datasets.
- Developed an automated simulation pipeline using Python and Scikit-Fuzzy.

<br>
<br>

_Developed by Des Djaja Mahesa_
