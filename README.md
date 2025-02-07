# Improved Electric Load Forecasting using Quantile Long Short-Term Memory Network with Dual Attention Mechanism
## Abstract
The robust and accurate load forecasting is necessary to ensure effective power market operations and optimize load dispatch strategies. Deep learning models have recently gained popularity because of their strong ability to learn data patterns. However, conventional deep-learning models still encounter difficulties in precisely predicting complex load patterns. This paper addresses the difficulties of forecasting intricate load patterns, where conventional deep learning models often fail. Therefore, a novel quantile long short-term memory network with dual attention is proposed for hour-ahead short-term load forecasting. By combining dual attention processes with quantile regression-based long short-term memory networks, the proposed framework effectively captures the temporal dependencies of the complex load pattern. The gates recurrent unit and hybridized methodologies of recurrent neural networks are among the baseline techniques against which the proposed method is thoroughly tested using datasets from Panama City and the Islamabad Electric Supply Company. The proposed quantile long short-term memory network with dual attention mechanism has demonstrated notable performance gains with 2.35% and 5.36% reduction in mean absolute percentage error in comparison to the best-performing models, from the set of baseline models, for the Panama and IESCO datasets, respectively. These results demonstrate the proposed method’s effectiveness in providing more improved and accurate forecasts for enhanced grid stability and economic dispatch efficiency. 

# Getting Started
Follow the steps below to set up.

## Prerequisites
Ensure you have the following software installed:<br>
- Python 3.10.9 or above<br>

Required libraries: <br>
 -  NumPy<br>
 -  Pandas<br>
 -  Scikit-learn<br>
 -  Matplotlib<br>
 -  Seaborn<br>
 -  TensorFlow<br>
 -  Keras<br>

# Running the Code
Run the DA-QLSTM, DALSTM.ipynb, LSTM.ipynb, GRU.ipynb, Simple RNN.ipynb, RNN-GRU.ipynb, RNN-LSTM.ipynb, QLSTM.ipynb and CNN-LSTM.ipynb scripts from respective folders to train and evaluate the proposed technique against benchmark techniques.

## Step 3: Visualization
Run the bar_plot.ipynb and graph.ipynb scripts to visualize the forecasting results and compare the model's performance.


Dual-Attention-Mechanism-Based-Quantile-LSTM/ <br>
├── Datasets/                          # Folder for datasets <br>
├── Simulation for IESCO dataset/      # Folder containing scripts for model training and evaluation for IESCO dataset <br>
├── Simulation for Panama dataset/     # Folder containing scripts for model training and evaluation for Panama dataset <br>
├── Graphicall illustration            # Folder containing scripts for result visualization <br>
├── README.md                          # Project README file <br>




## Reference
