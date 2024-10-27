# Dynamic-Pricing-XGBT
Dynamic Pricing Model Implementation on the US Airlines Industry


You can access the initial dataset from [here](www.dropbox.com/scl/fo/mybc5v9s800orsu78b6ao/h?rlkey=1an4ndcscd5uw9yi7oxx8ypfn&e=1&dl=0/)


# Dynamic Pricing Data Processing Pipeline

## Project Overview

This project preprocesses, encodes, and transforms airline itinerary data for a dynamic pricing model. The data processing pipeline consists of three main stages:

1. **Data Preprocessing**: Cleans and structures raw data for further processing.
2. **Encoding and Imputation**: Encodes categorical variables and handles missing values.
3. **Transformation Model**: Applies encoding techniques to prepare data for model training.

## Overview

### 1. Data Preprocessing (`dataPreprocessing.ipynb`)
   - **Objective**: Load and perform preliminary cleaning on airline itinerary data.
   - **Steps**:
     - Load data with Dask for efficient large-scale processing.
     - Perform basic statistics to understand the dataset.
     - Address multivalued attributes and filter data for model efficiency.
   
### 2. Encoding and Imputation (`EncodingAndImputation.ipynb`)
   - **Objective**: Standardize and encode data while managing missing values.
   - **Steps**:
     - Convert time fields to date formats for consistency.
     - Ensure appropriate data types across columns.
     - Apply categorical encodings to prepare data for downstream models.

### 3. Transformation Model (`transformationModel.ipynb`)
   - **Objective**: Apply advanced encoding methods to prepare data for model training.
   - **Steps**:
     - Frequency encoding of categorical columns.
     - Splitting data into categorical and numerical subsets for targeted transformations.

## Installation

To run the notebooks, install the following dependencies:

```bash
pip install pandas dask seaborn matplotlib torch



