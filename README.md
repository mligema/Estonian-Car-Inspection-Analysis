# Estonian Car Inspection Analysis

This project provides an analysis of Estonian car inspection data to uncover insights and predict inspection outcomes. Using a dataset containing vehicle inspection results, the project performs exploratory data analysis (EDA), generates visualizations, and builds a machine learning model to estimate the likelihood of a car passing or failing an inspection.

---

## Project Structure

```
Estonian-Car-Inspection-Analysis/
│
├── data/
│   └── yv-data-4.csv          # The dataset containing inspection results
│
├── notebooks/
│   └── inspection_analysis.ipynb # Jupyter Notebook for analysis and modeling
│
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
```

---

## Dataset

### File: `data/yv-data-4.csv`
The dataset contains information about:
- **Make (MARK)**: Manufacturer of the vehicle.
- **Model (MUDEL)**: Specific model of the vehicle.
- **Year_Built (VÄLJALASKEAASTA)**: Year the vehicle was manufactured.
- **Total_Inspections (ÜV)**: Total inspections performed.
- **Passed_Inspection (KORRAS ÜV)**: Number of inspections passed.
- **Failed_Inspection (KORDUS ÜV)**: Number of inspections failed.
- **Percentage_Failed (KORDUVA ÜV PROTSENT)**: Percentage of failed inspections.
- **Number_of_Vehicles (SOIDUKITE ARV)**: Count of vehicles inspected.
- **Average_Age (SOIDUKITE VANUS)**: Average age of vehicles inspected.

---

## Features

1. **Data Cleaning**:
   - Handles missing values.
   - Filters data for specific car manufacturers.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizes inspection trends.
   - Analyzes failure rates by make, model, and vehicle age.

---

## Visualizations
- Bar chart: Top 10 reliable car makes with the lowest failure rates.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mligema/Estonian-Car-Inspection-Analysis.git
   cd Estonian-Car-Inspection-Analysis
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Open `notebooks/inspection_analysis.ipynb` to explore the analysis.

---

## Requirements
The required Python libraries are listed in `requirements.txt`. Install them using `pip`:
```bash
pip install -r requirements.txt
```

---

## Usage

1. **Run the Notebook**:
   Open the Jupyter Notebook `notebooks/inspection_analysis.ipynb` to explore the data and generate insights.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.