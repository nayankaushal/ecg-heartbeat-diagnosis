# ecg-heartbeat-diagnosis
I will be analyzing the dataset containing 12552 Electrocardiogram (ECG) signals of single heartbeats and predicting whether the readings are normal or abnormal. The dataset has been derived from The PTB Diagnostic ECG Database. The ECG signals have been decomposed into 187 vectors. Each of the vectors provides measurements at consecutive time points. Preprocessing of the signals has been performed by cropping, down sampling to sampling frequency of 125Hz, and padding with zeroes if necessary. The response variable is a categorical variable indicating whether the heartbeat is normal or abnormal (0: normal, 1 abnormal).

To view the project, you can open the "ECG Heartbeat Diagnosis.Rmd" or "ECG Heartbeat Diagnosis.pdf". The explanation and interpretation of the results is consolidated in the "Report - ECG Heartbeat Diagnosis.pdf" file.
