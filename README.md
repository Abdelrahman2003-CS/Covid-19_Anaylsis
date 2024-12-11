# Covid-19_Anaylsis
# Country-Wise Data Analysis and Dashboard

This repository contains two Jupyter notebooks for analyzing and visualizing country-wise data from a dataset named `country_wise_latest.csv`. The notebooks focus on data preprocessing, exploration, and interactive visualization using Dash.

## Notebooks

### 1. Country_Wise.ipynb
#### Description
- Performs data preprocessing and exploration on the dataset.
- Includes renaming columns, inspecting data types, and generating visualizations.
- Provides insights into trends and distributions within the data.

#### Libraries Used
- `pandas` for data manipulation.
- `numpy` for numerical operations.
- `matplotlib` and `seaborn` for static visualizations.
- `plotly.express` for interactive visualizations.

#### Instructions
1. Ensure the dataset `country_wise_latest.csv` is in the same directory as the notebook.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
3. Run the notebook to explore and visualize the data.

---

### 2. CountryWiseDash.ipynb
#### Description
- Creates an interactive dashboard using Dash, specifically JupyterDash.
- Displays country-wise trends and metrics interactively.

#### Libraries Used
- `pandas` and `numpy` for data preprocessing.
- `plotly` for visualizations.
- `jupyter-dash` for building and running the dashboard within Jupyter Notebook.

#### Instructions
1. Ensure the dataset `country_wise_latest.csv` is in the same directory as the notebook.
2. Install the required libraries:
   ```bash
   pip install pandas numpy plotly jupyter-dash matplotlib seaborn
   ```
3. Run the notebook to launch the dashboard. Access it through the provided URL.

---

## Dataset
The dataset `country_wise_latest.csv` should contain the following columns:
- `Country/Region` (renamed to `Country`)
- `1 week % increase` (renamed to `One_Week_Increase_Perc`)

Ensure the dataset is properly formatted and placed in the project directory before running the notebooks.

---

## Outputs
- **Country_Wise.ipynb**: Static and interactive visualizations of country-wise data trends.
- **CountryWiseDash.ipynb**: A fully functional interactive dashboard for detailed exploration.

---

## Requirements
- Python 3.7+
- Jupyter Notebook or VS Code with Jupyter extensions

Install the dependencies:
```bash
pip install -r requirements.txt
```
(Manually create a `requirements.txt` file if not included, listing all necessary libraries.)

---

## Usage
1. Clone this repository and navigate to the project folder.
2. Place the `country_wise_latest.csv` file in the same directory as the notebooks.
3. Open the notebooks in Jupyter or VS Code and execute the cells sequentially.

---

## Acknowledgments
This project uses open-source libraries and the Dash framework for interactive visualizations.

