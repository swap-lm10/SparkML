# Spark Machine Learning Project
This is a project that demonstrates how to perform machine learning with Apache Spark using Jupyter Notebooks. In this project, we will use Spark's MLlib library to build a binary classification model that predicts area according to the rental price.

Dataset
We will be using the Ireland rental data. This dataset contains information about Ireland's rent according to county location, as well as type of house, no of bedrooms etc. The file IrelandRentalData.csv.zip in this repository contains a cleaned version of the dataset that we will use for this project.

Installation
1. Clone the repo
````
git clone https://github.com/swap-lm10/Spark-Machine-Learning.git
````
2. Install Anaconda or Miniconda (if not already installed)
````
# For Anaconda
https://www.anaconda.com/products/individual

# For Miniconda
https://docs.conda.io/en/latest/miniconda.html
````

3. Create a new conda environment and install the required packages
````
conda create --name sparkml python=3.7
conda activate sparkml
conda install -c conda-forge pyspark=3.1.1 findspark jupyterlab pandas numpy matplotlib seaborn
````

4. Start Jupyter Notebook
````
jupyter notebook
````

Usage
Open the Spark Machine Learning.ipynb notebook in Jupyter Notebook
Follow the instructions in the notebook to load the dataset, prepare the data, train a logistic regression model, and evaluate the model's performance.
Experiment with different hyperparameters and feature engineering techniques to try to improve the model's performance.
Contributing
Contributions are welcome! Please feel free to open an issue or pull request if you have any suggestions or improvements.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contact
If you have any questions or comments about this project, you can reach me at swapnilbhoite@live.com.

Enjoy using Spark Machine Learning!




