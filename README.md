# Capstone-project
Matric results EDA
This repository contains code for analyzing high school matriculation results using Python's pandas, seaborn, and matplotlib libraries. The analysis focuses on understanding the distribution of quintiles, percentage pass rates, relationships between various variables, and correlations among them.
##  Table of Contents
Introduction
Installation
Usage
Results
Contributing
License
## Introduction
The purpose of this analysis is to gain insights into high school matriculation results. The dataset used in this analysis is stored in a CSV file named matric_results.csv.
## Installation
Clone this repository
git clone https://github.com/Mfessy89/matriculation-analysis.git cd matriculation-analysis
Install the required Python libraries using pip: pip install pandas seaborn matplotlib
Place your matric_results.csv file in the same directory as the code files.
## Usage
Run the provided Python script using your preferred Python interpreter. Make sure the matric_results.csv file is in the same directory. The script will load the data, perform exploratory data analysis, and generate visualizations to help you understand the dataset better.
python analyze_matric_results.py
## Results
The analysis generates several visualizations to help you understand the data:

A histogram showing the distribution of quintiles.
A box plot illustrating the distribution of percentage pass rates by quintile.
A scatter plot depicting the relationship between the number of learners who wrote the exam and the number of learners who passed.
A heatmap displaying the correlation matrix of the dataset.
A pair plot showcasing multivariate relationships among variables, differentiated by quintile.
## Contributing
Contributions to this repository are welcome! If you have suggestions for improvements or new features, feel free to open an issue or create a pull request.

Fork the repository.
Create a new branch for your feature: git checkout -b feature-name.
Make your changes and commit them: git commit -m 'Add some feature'.
Push to the branch: git push origin feature-name.
Open a pull request detailing your changes.
## License
This project is licensed under the MIT License.
