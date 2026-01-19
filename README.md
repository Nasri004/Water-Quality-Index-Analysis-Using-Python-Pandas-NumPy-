# Water-Quality-Index-Analysis-Using-Python-Pandas-NumPy-
This project analyzes water quality data stored in Excel files using Python. Pandas and NumPy are used to preprocess data and calculate multiple Water Quality Indices (WAWQI, WGWQI, OWQI). The results classify water quality into standard categories to support environmental monitoring and decision-making.

## 📊 Dataset
- Input data is provided in Excel format (`WaterQuality01.xlsx`)
- Contains yearly measurements from multiple sampling points
- Parameters include:
  - pH
  - Temperature
  - Dissolved Oxygen
  - DBO5
  - Nitrates
  - Phosphates
  - Ammonium
  - Fecal Coliforms

## ⚙️ Methodology
1. Load Excel data using Pandas
2. Clean and preprocess the dataset
3. Assign standard values (Si) and weights (Wi)
4. Compute sub-indices for each parameter
5. Calculate:
   - WAWQI (Weighted Arithmetic WQI)
   - WGWQI (Weighted Geometric WQI)
   - OWQI (Overall WQI)
6. Classify water quality based on index thresholds


## 📈 Results
- Each sampling point is assigned numerical WQI values
- Water quality is classified into categories:
  - Excellent
  - Good
  - Fair
  - Poor
  - Very Poor
- Final results are stored in Pandas DataFrames

## ▶️ How to Run
1. Clone the repository:
   git clone https://github.com/your-username/your-repo-name.git
2. Install required libraries:
   pip install pandas numpy
3. Place the Excel file in the project directory(I will add it later)
4. Run the Python script or Jupyter Notebook

##NASRI
