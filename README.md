# soft-attention_LSTM_forecasting

## work in progress!

Soft attention mechanism with recurrent neural networks
Based on the paper: Forecasting stock prices with long-short term memory neural network based on attention mechanism, by Jiayu Qiu, Bin Wang, Changjun Zhou

The model has been adapted from the paper and has the following structure.

1) Dense
2) GRU (single layer)
3) Soft attention
4) Dense 

The model is applied to financial trading data of daily frequency. Inputs include technical indicators. Rolling windows of length 253 are used to calculate the 1 step ahead forecast of High and Low prices of the stock. This forecast is then applied to the loss function with the actual valies and the network is optimized over the two values of High and Low.

Work in progress, will be exploring wavelet transformations for time series denoising in the near future






