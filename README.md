# Daily Climate Forecasting

This project was done as the final project for the Data Mining course and focuses on **forecasting atmospheric pressure in Delhi** using historical climate data. The dataset was sequential and required several preprocessing steps such as scaling features with MinMaxScaler and removing outliers (especially in wind speed and mean pressure) using z-score thresholds. After cleaning, the data became suitable for time-series modeling.

To model the sequential patterns, I experimented with different deep learning approaches including **LSTM**, **RNN**, and **GRU** networks. The models were trained and evaluated with metrics such as MAE, MSE, RMSE, and R². While simple LSTM and RNN models performed reasonably well, they sometimes suffered from underfitting or overfitting depending on the chosen parameters. The **GRU model** achieved the best balance of accuracy and efficiency, producing predictions that closely matched the real test data with lower error and faster training time.

Overall, the project shows that GRU is a strong candidate for forecasting atmospheric pressure in this dataset, outperforming other recurrent models while also being computationally efficient.  
