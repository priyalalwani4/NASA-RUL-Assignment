# **Predictive Maintenance Using LSTM and GRU on NASA Turbofan Engine Dataset**

## **Overview**

This project focuses on predictive maintenance by predicting the **Remaining Useful Life (RUL)** of aircraft engines using **Long Short-Term Memory (LSTM)** networks and **Gated Recurrent Units (GRU)**. The dataset used is the **NASA CMAPSS Turbofan Engine Dataset (FD001)**, which provides time-series sensor data from turbofan engines.

In this project, we:
1. Preprocess the time-series data.
2. Build and compare LSTM and GRU models for RUL prediction.
3. Evaluate the models using various metrics like accuracy, precision, recall, and F1-score.

## **Project Structure**

The project consists of the following files:

- **`main_rul.ipynb`**: Jupyter Notebook containing the code for data preprocessing, model building, evaluation, and comparison of LSTM and GRU models.
- **`report_rul.pdf`**: A detailed report summarizing the project methodology, results, insights, and future work.
- **`README.md`**: This file, providing an overview of the project.

## **Running the Code**

You can run the code either on **Kaggle** or locally using **Jupyter Notebooks (IPYNB)**. Below are the steps:

### **Option 1: Running on Kaggle**

1. **Access Kaggle**:
   - Go to the [Kaggle website](https://www.kaggle.com/).
   - Sign in to your account (create an account if you don't have one).

2. **Create a New Kaggle Notebook**:
   - In your Kaggle account, create a new notebook by navigating to **Notebooks** and clicking **+ New Notebook**.

3. **Upload the Dataset**:
   - Add the **NASA CMAPSS dataset** to your Kaggle notebook:
     - Click on **Add Dataset** on the right-hand side of the notebook.
     - Search for the [NASA CMAPSS Turbofan Engine dataset](https://www.kaggle.com/datasets/behrad3d/nasa-cmaps) and add the `FD001` and `FD002` files to your notebook.

4. **Upload the Notebook**:
   - Upload the **`main_rul.ipynb`** file into your Kaggle notebook.
   - Alternatively, you can copy and paste the code from **`main_rul.ipynb`** into the cells of your Kaggle notebook.

5. **Run the Notebook**:
   - After setting up, run the cells in the notebook sequentially to preprocess the data, build the models, and evaluate their performance.
  
   - ### **Key Sections of the Notebook**

- **Data Preprocessing**: 
  - Preprocesses the FD001 dataset by handling missing data, normalizing the sensor readings, and applying advanced time-series feature engineering such as moving averages and trend extraction.
  
- **Model Building**:
  - Constructs and trains LSTM and GRU models on the preprocessed FD001 dataset to predict the Remaining Useful Life (RUL) of aircraft engines. The models are optimized using techniques such as dropout for regularization and Adam optimizer for gradient-based optimization.
  
- **Evaluation and Comparison**:
  - Evaluates the performance of both LSTM and GRU models using metrics like accuracy, precision, recall, and F1-score. Visualizations of actual vs predicted RUL are provided, along with comparisons of performance across the models.

