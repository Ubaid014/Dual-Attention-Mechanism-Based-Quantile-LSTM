# Improved Electric Load Forecasting using Quantile Long Short-Term Memory Network with Dual Attention Mechanism
## Abstract
The robust and accurate load forecasting is necessary to ensure effective power market operations and optimize load dispatch strategies. Deep learning models have recently gained popularity because of their strong ability to learn data patterns. However, conventional deep-learning models still encounter difficulties in precisely predicting complex load patterns. This paper addresses the difficulties of forecasting intricate load patterns, where conventional deep learning models often fail. Therefore, a novel quantile long short-term memory network with dual attention is proposed for hour-ahead short-term load forecasting. By combining dual attention processes with quantile regression-based long short-term memory networks, the proposed framework effectively captures the temporal dependencies of the complex load pattern. The gates recurrent unit and hybridized methodologies of recurrent neural networks are among the baseline techniques against which the proposed method is thoroughly tested using datasets from Panama City and the Islamabad Electric Supply Company. The proposed quantile long short-term memory network with dual attention mechanism has demonstrated notable performance gains with 2.35% and 5.36% reduction in mean absolute percentage error in comparison to the best-performing models, from the set of baseline models, for the Panama and IESCO datasets, respectively. These results demonstrate the proposed method’s effectiveness in providing more improved and accurate forecasts for enhanced grid stability and economic dispatch efficiency. 

# Getting Started
Follow the steps below to set up and run the code for short-term global horizontal irradiance forecasting.

## Prerequisites
Ensure you have the following software installed:<br>
- Python 3.10.9 or above<br>

Required libraries: <br>
 -  NumPy<br>
 -  Pandas<br>
 -  Scikit-learn<br>
 -  CatBoost<br>
 -  Matplotlib<br>
 -  Seaborn<br>
 -  TensorFlow<br>
 -  Keras<br>
 -  RandomForest<br>

# Running the Code
## Step 1: Data Preprocessing
Run k-mean_clustering.ipynb script to perform weather-based clustering.<br>
Run splitting_the_clustering_data.ipynb script to separate respective clusters.<br>

## Step 2: Model Training and Evaluation

Run the Bidirectional_LSTM.ipynb, GRU.ipynb, CatBoost.ipynb and adaboost.ipynb scripts from respective folders to train and evaluate the weather-classified CatBoost model against benchmark techniques.

## Step 3: Visualization
Run the bar_plot.ipynb, graph.ipynb and scatter_regression_plot.ipynb scripts to visualize the forecasting results and compare the model's performance.


Short-term-Global-Horizontal-Irradiance-Forecasting/ <br>
├── Datasets/                   # Folder for datasets <br>
├── Weather Calssification/     # Folder containing scripts for data preprocessing and clustering <br>
├── Simulation for/             # Folder containing scripts for model training and evaluation <br>
├── Graphicall illustration     # Folder containing scripts for result visualization <br>
├── README.md                   # Project README file <br>




## Reference
Please cite this work as:
"Ubaid Ahmed, Ahsan Raza Khan, Anzar Mahmood, Iqra Rafiq, Rami Ghannam, Ahmed Zoha,
Short-term global horizontal irradiance forecasting using weather-classified categorical boosting,
Applied Soft Computing,
2024,
111441,
ISSN 1568-4946,
https://doi.org/10.1016/j.asoc.2024.111441.
(https://www.sciencedirect.com/science/article/pii/S1568494624002151)"
