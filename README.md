# VMD-SSA-LSSVM-for-power-forecast
In this paper, LSSVM is used for short-term power load forecasting, and a short-term power load forecasting model based on LSSVM is proposed. At the same time, a Sparrow Algorithm (SSA) model is established to optimize the parameters of LLSVM to improve the forecasting accuracy. However, studies have shown that if a time series forecast model is built directly on the original series, the forecast data will lag the actual data. Such a model is meaningless. This is mainly due to the autocorrelation in the time series data, so I use VMD decomposition The method decomposes the original sequence, then models each sequence separately, and finally adds the results of each sequence test set as the final result. The comparative analysis results show that the prediction accuracy of this model is better than that of many other prediction models, and this model shows better performance in short-term load forecasting.
