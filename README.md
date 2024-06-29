# IronProgress Project

This repository contains the files and resources for the IronProgress project, which involves data analysis and prediction of house prices in King County.

## Files

### Jupyter Notebook
- **IronProgress.ipynb**: This Jupyter notebook contains the data processing and analysis steps for the IronProgress project. The notebook performs the following tasks:
  - Imports necessary libraries (pandas, numpy, matplotlib, seaborn).
  - Loads the dataset from a CSV file.
  - Explores the dataset by displaying initial rows and checking for missing values.
  - Cleans the data by handling missing values, removing unnecessary columns, and engineering new features (e.g., `year_sold`, `season_sold`, `house_age`).
  - Analyzes the data to find correlations between features and the target variable (`price`).
  - Visualizes the analysis results using bar charts, histograms, and correlation matrices.
  - Trains multiple regression models (Linear Regression, Ridge Regression, Lasso Regression, Random Forest, Gradient Boosting) to predict house prices.
  - Evaluates the models based on performance metrics like RMSE and cross-validation scores.

### PowerPoint Presentation
- **King County Houses.pptx**: This PowerPoint presentation provides an overview of the IronProgress project. It includes slides covering:
  - Introduction to the project and its objectives.
  - Methodology used for data collection and analysis.
  - Key findings from the data analysis.
  - Visualizations of the results.
  - Conclusions and future work.

## Usage

### Jupyter Notebook
1. Open the `IronProgress.ipynb` file using Jupyter Notebook or Jupyter Lab.
2. Execute the cells sequentially to perform data processing, analysis, and visualization.
3. Review the outputs and visualizations generated in the notebook.

### PowerPoint Presentation
1. Open the `King County Houses.pptx` file using Microsoft PowerPoint or any compatible presentation software.
2. Navigate through the slides to understand the project's objectives, methodology, key findings, and conclusions.

## Requirements
- Python 3.x
- Jupyter Notebook or Jupyter Lab
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, please contact Dean Gani.
