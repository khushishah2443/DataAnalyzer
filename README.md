# DataAnalyzer

An interactive **data analysis and visualization web app** built with **Python, Streamlit, and Pandas**.  
DataAnalyzer allows users to upload a dataset, explore summary statistics, generate basic charts, and perform simple data operations through an easy-to-use interface.

---

## Overview

DataAnalyzer is a lightweight tool designed for quick exploratory data analysis. It helps users inspect datasets without writing code by providing:

- Dataset upload functionality  
- Basic descriptive statistics  
- Interactive visualizations  
- Simple data operations such as dropping columns  

This project is useful for beginners learning data analysis as well as for quickly understanding small datasets.

---

## Features

- Upload datasets in **CSV** format  
- Preview dataset structure and dimensions  
- Generate **line charts**, **bar charts**, and **scatter plots**  
- View **descriptive statistics** for selected columns  
- Perform simple preprocessing operations like **dropping columns**  
- Navigate between different sections using a sidebar menu  

---

## Tech Stack

- **Python**
- **Streamlit**
- **Pandas**

---

## Project Structure

```bash
DataAnalyzer/
│── dwm.py
│── README.md
```

## How It Works

The application is divided into four sections:

### 1. Home
Displays a basic introduction and allows the user to upload a dataset.

### 2. Data Visualization
Users can select columns and generate:
- Line chart
- Bar chart
- Scatter chart

### 3. Data Analysis
Users can select columns and view descriptive statistics such as:
- Count
- Mean
- Standard deviation
- Minimum and maximum values
- Quartiles

### 4. Data Operations
Users can perform simple transformations such as:
- Dropping a selected column from the dataset

---
