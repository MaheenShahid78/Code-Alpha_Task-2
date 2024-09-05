#Feature Engineering with Machine Failure Dataset
This project demonstrates the process of feature engineering using a dataset related to machine failures. The notebook includes steps to load the dataset, check for missing values, and create new features that can be used for predictive modeling.

#Contents

Data Loading: Importing the dataset and displaying the first few rows.
Missing Values Check: Identifying and handling missing data in the dataset.

#Feature Creation:

Time-based features
Rolling statistics for temperature, rotational speed, and torque

#Requirements

Python 3.x
Pandas
NumPy
You can install the required packages using:
bash
pip install pandas numpy
Usage
Clone the repository:https://github.com/MaheenShahid78/Code-Alpha_Task-2
bash
git clone https://github.com/MaheenShahid78/Code-Alpha_Task-2

Navigate to the project directory:
bash
cd your-repo-name
Run the Jupyter Notebook:
bash
jupyter notebook Feature\ Engineering.ipynb
Dataset
The dataset used in this project contains various parameters related to machine operations, such as air temperature, process temperature, rotational speed, torque, and tool wear. It also includes labels indicating machine failures.

Feature Engineering
The key feature engineering techniques applied in this project include:

Time Index: A sequential index representing the order of data points, which can be useful in time-series analysis.
Rolling Statistics: Calculating the rolling averages of key parameters like air temperature, rotational speed, and torque over a defined window to smooth out short-term fluctuations and highlight longer-term trends.

License
This project is licensed under the MIT License. See the LICENSE file for more details
