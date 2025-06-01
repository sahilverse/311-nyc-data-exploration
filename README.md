# NYC 311 Service Request Analysis

This project explores 311 service request data from New York City, covering complaints submitted by residents from 2010 to the present. It performs data cleaning, transformation, statistical analysis, and visualization to uncover trends and insights about complaint types, resolution times, and geographic patterns.

## 📁 Dataset

**Source**: NYC Open Data  
**File**: `Customer Service_Requests_from_2010_to_Present.csv`  
This dataset includes complaint types, location info, created and closed timestamps, agency responses, and more.

## 📂 Link for the Data
[Click here to download the dataset](https://www.dropbox.com/scl/fo/s42jh8gl4go3zugkv35hq/ALmOdUlSyX3WP-4t-kRTro4?rlkey=mdapp4glk5wyzeku6e5vkizxr&st=pndtcplt&dl=0)

## 📊 Features

- Load and clean a large-scale dataset using `pandas`
- Convert and engineer datetime features
- Drop irrelevant columns and handle missing values
- Explore complaint types, request closing time, and locations
- Generate visual insights using `matplotlib`
- Perform statistical tests (ANOVA, Chi-Square) with `scipy`

## 📌 Key Insights

- Most common complaint types in NYC
- Average time taken to resolve each complaint type
- Trends in service requests over time
- Relationship between complaint types and location categories

## 📈 Visualizations

- Bar chart of top 10 complaint types
- Histogram of request closing times
- Line chart showing monthly request trends
- Bar chart of average closing time by complaint type
- Stacked bar of average closing time by location type

## 🧪 Statistical Analysis

- **ANOVA Test**: To check if average resolution times vary across complaint types
- **Chi-Square Test**: To assess dependency between complaint types and location types

## 🛠 Tech Stack

- Python
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- scipy

## 📂 Project Structure

```
main.ipynb                      # Main notebook with full analysis
data/
├── Customer Service_Requests_from_2010_to_Present.csv
```

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib scipy
   ```
3. Open `main.ipynb` in Jupyter Notebook or VSCode
4. Run cells step-by-step

## 📝 License

This project is for educational and research purposes only. Original dataset © NYC Open Data.
