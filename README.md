---

# Data Engineering and Machine Learning with Apache Beam

This repository contains three assignments that demonstrate the application of various Apache Beam features, Auto EDA tools, and machine learning integration using BeamML. The projects are developed in **Google Colab** and utilize **Apache Beam**, **Sweetviz**, and **BeamML** to process, visualize, and analyze data.

---

## Table of Contents

- [Assignment 1: Complete Dataset EDA](#assignment-1-complete-dataset-eda)
- [Assignment 2: Auto EDA with Sweetviz](#assignment-2-auto-eda-with-sweetviz)
- [Assignment 3: Apache Beam Features Demonstration](#assignment-3-apache-beam-features-demonstration)
- [Requirements](#requirements)
- [Usage](#usage)

---

## Assignment 1: Complete Dataset EDA

In this assignment, we perform **Exploratory Data Analysis (EDA)** on the [Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn) dataset using **advanced D3.js visualizations**. This part of the project focuses on insightful and interactive visualizations that help in understanding the dataset comprehensively.

### Key Features:
- **Advanced EDA**: Analysis using sophisticated visualizations.
- **Insights**: Highlighting key features influencing customer churn.
- **Interactive Visuals**: D3.js based graphs for exploratory analysis.

### Link to the Colab Notebook:
[Assignment 1 - Complete Dataset EDA](https://colab.research.google.com/drive/1zU2RRg3Rt0e8a0UkIZI6zwP2v9w-uYLC?usp=sharing)

---

## Assignment 2: Auto EDA with Sweetviz

In this assignment, we use **Sweetviz** to perform **Automated Exploratory Data Analysis (Auto EDA)** on the Telco Customer Churn dataset. Sweetviz generates a visually appealing and comprehensive report that includes detailed data distribution, comparisons, and feature relationships.

### Key Features:
- **Sweetviz Integration**: Automatically generates visual EDA reports.
- **Target Analysis**: Analysis is focused on the "Churn" target variable.
- **Comparison Reports**: Highlights differences between churned and non-churned customers.

### Link to the Colab Notebook:
[Assignment 2 - Auto EDA with Sweetviz](https://colab.research.google.com/drive/145aG9moJMqjMpXCdx--sL-MfdeChFTA-?usp=sharing)

---

## Assignment 3: Apache Beam Features Demonstration

This assignment demonstrates several core features of **Apache Beam** and showcases how to integrate **BeamML** for machine learning inference. The assignment is divided into multiple parts, each showcasing a key feature of Beam:

### Features Demonstrated:
1. **Composite Transform**: Demonstrates grouping of multiple transforms into a reusable unit.
2. **Pipeline I/O**: Shows how to read from and write to external files (CSV, text).
3. **Triggers and Windowing**: Highlights how to process streaming data using time-based windowing.
4. **ParDo**: Demonstrates parallel processing of elements.
5. **Streaming**: Implementing real-time data streaming pipelines with Apache Beam.
6. **BeamML Integration**: Using machine learning models for real-time inference with BeamML.

### Link to the Colab Notebook:
[Assignment 3 - Apache Beam Features Demonstration](https://colab.research.google.com/drive/1YWXeFSW1RAkhOMgrEYGJk8CM9L9UC9TH?usp=sharing)

---

## Requirements

To run the code in this repository, you need the following libraries:

- **Google Colab**: All the code is designed to run on Google Colab.
- **Apache Beam**: Install Apache Beam with the following command:
  ```bash
  !pip install apache-beam[interactive]
  ```
- **Sweetviz**: Install Sweetviz for Auto EDA:
  ```bash
  !pip install sweetviz
  ```
- **Pandas**: For data handling and manipulation.
  ```bash
  !pip install pandas
  ```

---

## Usage

Follow the steps below to run the assignments:

### Assignment 1: Complete Dataset EDA
1. Open the [Assignment 1 Colab Notebook](https://github.com/Mohib1402/ApacheBeam/blob/main/ApacheBeamAss1.ipynb).
2. Load the Telco Customer Churn dataset and run all cells.
3. Review the advanced D3.js visualizations for insights.

### Assignment 2: Auto EDA with Sweetviz
1. Open the [Assignment 2 Colab Notebook](https://github.com/Mohib1402/ApacheBeam/blob/main/ApacheBeamAss2.ipynb).
2. Load the Telco Customer Churn dataset and run all cells.
3. Review the Sweetviz-generated report and comparison between churned and non-churned customers.

### Assignment 3: Apache Beam Features Demonstration
1. Open the [Assignment 3 Colab Notebook](https://github.com/Mohib1402/ApacheBeam/blob/main/ApacheBeamAss3.ipynb).
2. Run each step of the pipeline to demonstrate:
   - Composite Transforms
   - Pipeline I/O (reading from and writing to CSV/text files)
   - Triggers and Windowing (streaming data)
   - ParDo for parallel data processing
   - BeamML for machine learning inference in a streaming pipeline
3. Explore the real-time results and ML integration with Apache Beam.

---

## Video Demonstration

For each assignment, video explanations have been created to walk through the steps. You can find the video in [here](./videos).

---
