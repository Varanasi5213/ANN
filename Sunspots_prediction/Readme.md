## Sunspots_prediction
**Description**
> The idea is to predict the pattern of sunspots in the given dataset.

**Work Details**
1. This is univariate time-series data, where we have a single value changing over time.
2. Time Series prediction is typically using the previous data pattern to find the next values. The length of the previous data pattern is called window size.
3. Here the window size is 30. So input will be 30 values and output will be the 31st value.
4. RNN's are best for understanding the time series data since it has memory cells and LSTM is a specialized RNN's to understand the long-term relations between the features.
5. The use of 1D CNN's is used in the initial layer to capture the spatial information along with temporal.
