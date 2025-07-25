# 🔍 Boston-Crime-Data-Exploratory-Analysis-using-Python


This project performs Exploratory Data Analysis (EDA) on the Boston Police Department Crime Incident Reports. Using Python and pandas, it dives into patterns, trends, and anomalies in crime data across the city.  
The accompanying notebook includes detailed preprocessing, visualization, and analysis steps.

---

## 📁 Dataset

The analysis is based on a dataset containing historical crime incident reports in Boston.  
The dataset includes:

- Incident number
- Offense group and description
- Date and time of occurrence
- UCR Part classification (Part One/Two/Three)
- District and street location
- Latitude and longitude for mapping

📌 **File used**: `crime.csv`

---

## 📊 What’s in the Notebook?

The notebook `Boston-Crime-Data-Exploratory-Analysis-using-Python.ipynb` includes:

### ✅ Key Steps:
1. **Importing Libraries**  
   Libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, etc.

2. **Data Loading**  
   - Read CSV using proper encoding (`ISO-8859-11`)
   - Encoding detection using Python's `encodings.aliases`

3. **Data Cleaning**  
   - Duplicate removal  
   - Handling missing values  
   - Parsing datetime formats  
   - Setting `OCCURRED_ON_DATE` as datetime index

4. **Exploratory Analysis**  
   - Crime count by **year**, **month**, **hour**, and **weekday**  
   - Distribution of crime types  
   - Analysis by **district** and **UCR_PART classification**

5. **Visualizations**  
   - Bar plots for crime frequency  
   - Time series plots of crime trends  
   - Heatmaps for hourly/day patterns  
   - Distribution of offenses per police district

---

## 🛠️ Technologies Used

- Python 3.x  
- pandas  
- matplotlib  
- seaborn  
- numpy  
- Jupyter Notebook  

---

## 📁 Project Structure

```bash
├── crime.csv                      # Crime dataset used for analysis
├── Boston-Crime-Data-Exploratory-Analysis-using-Python.ipynb   # Jupyter notebook with EDA
├── README.md                     # This file

