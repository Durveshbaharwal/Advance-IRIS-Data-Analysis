# Advance Iris Dataset Analysis and Visualization
This project aims to analyze the famous Iris dataset using various visualization techniques to better understand the relationships between the features and how they contribute to the differentiation of species. We have included multiple types of visualizations to explore the dataset and added insights drawn from each plot. The project is especially useful for those who are new to exploratory data analysis (EDA) and clustering techniques.

## Project Summary

We explored the Iris dataset using the following techniques:
- Pairplot (Seaborn)
- Scatter Plot (Sepal Length vs. Sepal Width)
- 3D Scatter Plot (Matplotlib)
- Interactive 3D Plot (Plotly)
- Correlation Heatmap (Seaborn)

These visualizations helped in understanding the relationships between the four key features of the dataset:
1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

## Key Findings:
- **Pairplot**: Showed clear clustering, especially between petal length and petal width.
  ![image](https://github.com/user-attachments/assets/bd550774-9b55-488a-bb8f-92a58762973e)

- **Scatter Plot (Sepal Length vs Sepal Width)**: Indicated less distinct separation between species based on sepal dimensions.
  ![image](https://github.com/user-attachments/assets/65341b62-09df-4d43-81d7-f3bedec4ef2a)

- **3D Scatter Plot**: Enhanced visualization of clusters by incorporating petal length along with sepal dimensions.
  ![image](https://github.com/user-attachments/assets/acc554ab-a554-45e3-b098-33ed6f84062d)

- **Interactive 3D Plot**: Allowed dynamic interaction with the plot for a more in-depth analysis.
  ![newplot](https://github.com/user-attachments/assets/240bbbaa-86e3-485d-8288-49dd06280844)

- **Correlation Heatmap**: Showed strong correlations between petal length and petal width, reaffirming their importance in species differentiation.
  ![image](https://github.com/user-attachments/assets/590ab91a-01de-42eb-831a-5c07bf3631ee)


## Repository Contents
This repository contains the following files:
1. `IRIS-Data-Analysis.ipynb`: The Jupyter Notebook with the complete analysis and code for the project.
2. `iris.csv`: The Iris dataset in .csv format.
3. `README.md`: This README file explaining the project and how to run it.

## Requirements
The following Python libraries are required to run the project:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- sklearn

You can install all the dependencies using the following command: 
``` bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```
## Data Source
The Iris dataset is available through the sklearn library:

``` python
from sklearn.datasets import load_iris
data = load_iris()
```

## Usage
1. Clone the repository:

```bash
git clone https://github.com/yourusername/iris-data-analysis.git
cd iris-data-analysis
```

2. Run the Jupyter notebook (IRIS-Data-Analysis.ipynb) to execute the code and see the visualizations.

```bash
jupyter notebook IRIS-Data-Analysis.ipynb

```
3. Follow the steps in the notebook to generate the visualizations and insights.

## Conclusion
Through various types of visualizations and clustering techniques, we discovered that petal length and petal width are the most important features for distinguishing between the three Iris species. The visualizations offered both numerical and graphical insights into the dataset, improving our understanding of its structure.

## Potential Improvements:
- Incorporate advanced clustering algorithms (e.g., K-Means, DBSCAN).
- Add more advanced visualizations like PCA plots or Hierarchical Clustering.
- Use machine learning models to further validate the clusters.

## Contribution
Contributions are welcome! If you have any improvements or suggestions, feel free to submit a pull request or open an issue.
