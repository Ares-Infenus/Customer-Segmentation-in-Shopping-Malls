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
## Resultados
El análisis identificó segmentos de clientes significativos basados en patrones de gasto y atributos demográficos. Entre los insights clave se destacan:

Clientes jóvenes con bajos ingresos pero alta tendencia al gasto.

Individuos de altos ingresos con comportamientos de gasto moderado a alto.

Diferencias conductuales en la segmentación basada en el género.

Para una discusión completa de los resultados, consulta el archivo Documentation.pdf en la carpeta reports.

---
## Trabajo Futuro
Incorporar variables psicográficas adicionales para refinar la segmentación.

Explorar técnicas de clustering alternativas (DBSCAN, clustering jerárquico).

Implementar un dashboard interactivo para análisis en tiempo real.

---
## Agradecimientos
Este proyecto se realizó como parte de un estudio avanzado de machine learning. Los datos fueron obtenidos de Kaggle a partir del dataset "Mall_Customers".

Licencia
Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

Contacto
Para consultas o colaboraciones, por favor contacta a Sebastián D. Pinzón Zambrano:
Correo: spinzonzambrano@gmail.com