****Meteorite Landings Analysis****
***Overview***

This project analyzes a dataset of meteorite landings using PySpark for large-scale data processing and Python visualization tools. The goal is to explore patterns in meteorite composition, geographic distribution, and mass.

🔧 Technologies Used
Python
PySpark
Pandas
Matplotlib

***Dataset***

The dataset contains recorded meteorite landings, including:

Name and classification
Mass (grams)
Latitude and longitude
Year of discovery

***Data Processing***

The workflow includes:

Cleaning and formatting the dataset
Converting data types for analysis
Handling missing values
Creating new features such as:
Iron classification (High Iron vs Not High Iron)
Geographic quadrants (NE, NW, SE, SW)
📈 Analysis Performed
Count of meteorites by composition
Distribution of meteorites by global quadrant
Average mass by region
Visualization of landing locations using scatter plots

***How to Run***

Install dependencies:

pip install pyspark pandas matplotlib

Open the notebook:

jupyter notebook landings.ipynb
Run all cells to reproduce the analysis

***Key Insights***
Meteorite landings are not evenly distributed globally
Iron-based meteorites can be identified and compared to others
Regional differences exist in meteorite mass and frequency
📝 Notes
Large datasets are processed using PySpark for performance
Only sampled data is used for visualization to improve speed
