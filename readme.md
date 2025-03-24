# Customer Segmentation in Shopping Centers
This repository contains the code and documentation for an advanced customer segmentation analysis using the K-means clustering algorithm. The project explores shopping behavior in shopping centers, leveraging demographic and behavioral data to identify meaningful customer segments.

Through a rigorous preprocessing process, statistical validation, and machine learning techniques, the analysis provides actionable insights for segmented marketing strategies. The accompanying documentation follows a scientific approach, ensuring methodological rigor and reproducibility.

---

## Features

- **Data Preprocessing:** Normalization and winsorization to handle scale differences and address outliers.
- **Cluster Validation:** Use of multiple indices (Elbow Method, Silhouette Coefficient, Dunn's Index, among others) to determine the optimal number of clusters.
- **Gender Segmentation:** Independent analysis for male and female customers, revealing behavioral patterns based on gender.
- **Correlation Analysis:** Identification of relationships between variables such as age, income, and spending score.
- **Advanced Visualization:** Use of heat maps, 3D graphs, and regression models to improve the interpretability of results.

---

## Repository Structure
```text
Copy
Edit
DO:
│ .gitignore # Files and folders ignored by Git
│ readme.md # Current README file (this document)
│
├───data # Project data
│ └───raw # Raw data
│ Mall_Customers.csv # Main dataset
│
├───reports # Generated reports and documentation
│ │ Documentation.pdf # Final PDF document
│ │ ... (other LaTeX files)
│ │
│ ├───plots_investing # Generated charts (summary images)
│ │ Chart 1.png # Example of generated chart
│ │ Chart 2.png # Example of generated graph
│ │ ... # Other graphs (numbered sequentially)
│ │
│ └───references # References and supporting studies
│ A joint model for online shopping malls.pdf
│ A segmentation study of Israeli shopping mall customers.pdf
│ ... (other documents)
│
└───src # Source code for the analysis
project_segmentation_code.ipynb # Notebook with the implementation
```

Note: In the plots_investing folder, the file names have been summarized to represent multiple generated graphs (Chart 1.png, Chart 2.png, etc.) without listing each one individually.

---

## Installation
Make sure you have Python version 3.x installed. This project requires the following libraries:

pandas

fatted

matplotlib

seaborn

scikit-learn (for StandardScaler)

statistical models

rich

scienceplots

Additionally, scienceplots and a LaTeX distribution are required to generate PDF documentation.

You can install all dependencies using pip:

```
pip install pandas numpy matplotlib seaborn scikit-learn statistical models rich scientific plots
```
If you prefer to use a virtual environment, follow these steps:

```
python -m venv env
source env/bin/activate # On Windows: env\Scripts\activate
pip install pandas numpy matplotlib seaborn scikit-learn statistical models rich scientific plots
```
Remember that to compile the documentation in LaTeX, you must have a LaTeX system installed (e.g., TeX Live or MiKTeX).

---

## Usage
Clone the Repository
Use the following command to clone the repository:

```
git clone https://github.com/Ares-Infenus/Customer-Segmentation-in-Shopping-Malls.git
cd Customer-Segmentation-in-Shopping-Malls
```
---

## Run the Notebook
Notebook Launch Jupyter:

```
Jupyter notebook
```
Open the project_segmentation_code.ipynb file located in the src folder and run the cells sequentially.

---

## Key Analytic Steps
Load the dataset: Import and inspect the data contained in Mall_Customers.csv.

Cleaning and Preprocessing: Handle missing values, feature normalization, and outlier handling.

Exploratory Data Analysis (EDA): Generation of descriptive statistics and visualizations.

Selection of the Optimal Number of Clusters: Calculation of validation metrics to determine the optimal k value.

Clustering and Interpretation: Application of K-means and analysis of the characteristics of each cluster.

---
## Results
The analysis identified significant customer segments based on spending patterns and demographic attributes. Key insights include:

Young customers with low incomes but high spending propensity.

High-income individuals with moderate to high spending behaviors.

Behavioral differences in gender-based segmentation.

For a full discussion of the results, see the Documentation.pdf file in the reports folder.

---
## Future Work
Incorporate additional psychographic variables to refine the segmentation.

Explore alternative clustering techniques (DBSCAN, hierarchical clustering).

Implement an interactive dashboard for real-time analysis.

---
## Acknowledgments
This project was conducted as part of an advanced machine learning study. Data was obtained from Kaggle using the "Mall_Customers" dataset.

License
This project is distributed under the MIT license. See the LICENSE file for details.

Contact
For inquiries or collaborations, please contact Sebastián D. Pinzón Zambrano:
Email: spinzonzambrano@gmail.com