# Predicting Heart Disease Prevalence with Distributed File System and Computing Machine Learning using PySpark

This repository contains a scalable and efficient implementation of machine learning algorithms to predict the prevalence of heart disease based on various independent parameters. The project leverages the power of distributed computing using PySpark and Hadoop Distributed File System (HDFS) to handle large datasets and provide real-time insights. The goal is to help medical professionals and researchers better understand and identify risk factors, ultimately contributing to early diagnosis and prevention of heart disease.

## Important Note

Please be aware that the tables and charts generated within this project may not be displayed correctly without re-running the code on a distributed file system like HDFS. Due to the nature of distributed computing and file storage, the visuals might appear differently when viewed directly on GitHub or other non-distributed platforms. To ensure accurate representation, we recommend running the project on a distributed file system as intended.

## Getting Started

These instructions will guide you through setting up the environment, running the project, and interpreting the results.

### Prerequisites

- Python 3.6 or later
- PySpark 3.1.2 or later
- Hadoop 3.3.0 or later (for HDFS)

### Installation

1. Clone this repository to your local machine.
2. Install the required Python packages: including PySpark, Pandas, Matplotlib, Numpy & Seasborn
3. Set up the Hadoop and PySpark environment following the official documentation.

### Running the Project

1. Load the dataset into HDFS.
2. Update the dataset path in the `config.py` file to point to your HDFS dataset location.
3. Run the main script: `python main.py`

### Results Interpretation

After running the project, you should see the results in the form of tables and charts, which will provide insights into the performance of various machine learning algorithms used in the prediction of heart disease prevalence. You can compare the performance metrics, such as accuracy and F1 score, to determine the most suitable model for your needs.
