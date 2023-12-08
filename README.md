# Provincial SEIR LSTM
This project aims to predict the outbreak of COVID-19 in Hubei by using the SEIR model, which is a classic infectious disease dynamics model. The model uses the contact rate to control the degree of intervention and highlights the importance of prevention and control measures.

In addition, the project uses the LSTM neural network to make predictions. By inputting data from the first three days, the network predicts the data for the fourth day. The next step is to include intervention values as input, optimize the sequence length of input and output, and improve the quality of predictions.

The project combines the SEIR model and LSTM predictions to forecast the trend of COVID-19 epidemics.

Some figures:
![image](https://github.com/AndyYue1893/Novel-Coronavirus-Pneumonia-SEIR-LSTM/blob/master/SEIR_basic.png)
![image](https://github.com/AndyYue1893/Novel-Coronavirus-Pneumonia-SEIR-LSTM/blob/master/SEIR_20200123_Intervention.png)![image](https://github.com/AndyYue1893/Novel-Coronavirus-Pneumonia-SEIR-LSTM/blob/master/SEIR_20200202_Intervention.png)
![image](https://github.com/AndyYue1893/Novel-Coronavirus-Pneumonia-SEIR-LSTM/blob/master/NCP_active_predict.png)![image](https://github.com/AndyYue1893/Novel-Coronavirus-Pneumonia-SEIR-LSTM/blob/master/NCP_new_predict.png)![image](https://github.com/AndyYue1893/Novel-Coronavirus-Pneumonia-SEIR-LSTM/blob/master/NCP_cum_pred.png)
