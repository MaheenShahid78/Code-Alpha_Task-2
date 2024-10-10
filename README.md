# Feature Engineering with Machine Failure Dataset

This project demonstrates the process of feature engineering using a dataset related to machine failures. The notebook includes steps to load the dataset, check for missing values, and create new features that can be used for predictive modeling.

## Contents

- Data Loading: Importing the dataset and displaying the first few rows.
- Missing Values Check: Identifying and handling missing data in the dataset.

## Feature Creation:

- Time-based features
- Rolling statistics for temperature, rotational speed, and torque

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites
Ensure you have the following installed:

Python 3.x
Jupyter Notebook
Required Python libraries (listed in requirements.txt)

## Installation

1. Clone the repository:
    bash
    git clone https://github.com/MaheenShahid78/Code-Alpha_Task-2
    

2. Create a virtual environment and activate it:
    bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    

3. Install the required libraries:
    bash
    pip install -r requirements.txt

### Usage

1. Start the Jupyter Notebook:
    bash
    jupyter notebook
   
2. Open the Feature Engineering.ipynb notebook and run the cells to execute the code step-by-step.

## Project Structure

- Feature Engineering.ipynb: The main Jupyter Notebook containing the code and explanations.
- data/: Directory containing the dataset (if any).
- requirements.txt: List of required Python libraries.

## Dataset

The dataset used in this project contains various parameters related to machine operations, such as air temperature, process temperature, rotational speed, torque, and tool wear. It also includes labels indicating machine failures.

## Feature Engineering Techniques

The key feature engineering techniques applied in this project include:

1. Time Index:

A sequential index representing the order of data points, which can be useful in time-series analysis.

2. Rolling Statistics: 

Calculating the rolling averages of key parameters like air temperature, rotational speed, and torque over a defined window to smooth out short-term fluctuations and highlight longer-term trends.

## Results

The notebook includes feature engineering techniques that can be applied to build predictive models for machine failure. These features will help improve the performance of models used for failure prediction.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


## License

This project is licensed under the MIT License. See the LICENSE file for more details

## Contact

Feel free to reach out if you have any questions or suggestions:

- Email: maheenshahid0302@gmail.com

