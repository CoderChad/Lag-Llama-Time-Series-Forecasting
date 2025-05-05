# Lag-Llama-Electricity-Demand-Forecasting
 
 ## Project Overview
 
 This project implements a Lag-Llama model for accurate electricity demand forecasting. Lag-Llama adapts the powerful Llama architecture for time series prediction by incorporating temporal features and lag components, making it particularly effective for electricity demand modeling.
 The system achieves high accuracy by capturing multiple seasonality patterns (daily, weekly, and seasonal) and special events that influence electricity usage.
 
 
 ## Key Features
 
 * Multi-horizon forecasting: Predicts electricity demand 24 hours ahead with recursive prediction strategy   <br>
 * Feature engineering pipeline: Incorporates temporal features, lag variables, and rolling statistics   <br>
 * Attention-based architecture: Uses self-attention mechanisms to model complex dependencies in consumption data   <br>
 * Robust data processing: Includes normalization, missing value handling, and outlier management  <br>
 * Interactive visualizations: Compare actual vs predicted demand with customizable plots  <br>
 
 
 ## Technologies Used
 
 PyTorch: Deep learning framework for model implementation   <br>
 Transformer architecture: Modified with RMSNorm layers similar to Llama design  <br>
 NumPy/Pandas: Data processing and manipulation  <br>
 Matplotlib: Visualization of forecasts and actual values  <br>
 scikit-learn: Data preprocessing and evaluation metric  <br>
