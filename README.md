# First-Chat-bot
RNN + GRU based chat bot

Pytorch was used for this task. 
Initially the data was cleaning and all rare words together with sentences longer than 10 words were removed . 

This is a conventional RNN + GRU implementation, shown in the image below. 

Why GRUs instead of LSTM ? 
GRUs perform better than LSTMs in RNN 

![] Capture_model.png

A bidirectional implementation in my model was done. Accounting for the past data input as well as the future input. 

![] Capture_model_2.png

