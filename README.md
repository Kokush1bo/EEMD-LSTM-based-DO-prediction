Approach: Use EEMD to decompose the time series data, use the individual IMFs to train model, get predictions from the model. Later, merge the predictions to obtain results and visualise them.

Main components of this repository:

* imf_decomposition: this file contains code to do EEMD on the given time series data. IMFs are then used to train the model.
* LSTM model file: this python file contains the code for the LSTM model which was used to train the model on IMFs we got from imf_decomposition file. From here we also get predictions which are then used to plot results and get final results.
* preds compiler file: this file was used to compile the preds from LSTM model, plot was made to visualise results and various statistical parameters were also calculated to measure model performance.
* eemd-lstm-res.rar: this file contains all the results obtained, with plots.
