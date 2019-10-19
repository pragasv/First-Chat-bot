# First-Chat-bot
RNN + GRU based chat bot

Pytorch was used for this task. 
Initially the data was cleaning and all rare words together with sentences longer than 10 words were removed . 

This is a conventional RNN + GRU implementation, shown in the image below. 

Why GRUs instead of LSTM ? 
GRUs perform better than LSTMs in RNN 

![](Capture_model.PNG)

A bidirectional implementation in my model was done. Accounting for the past data input as well as the future input. 

![](Capture_model_2.PNG)

The implementation also consits of a single layered attention mechasnism 

![](Capture_attn.PNG)

After 4000 iterations the following losses were incurred

![](Capture3.PNG)

The trained chatbots responses for inputs were as below

![](Capture_output.PNG)

Conclusion :- 
There is room for development in making the bot understand the statements between a question and a statement 
Better and more datasets would be a way forward with , higher number of iterations. 
Complex attention mechanisms would be a way forward for better response. 
And complex encoder and decoder structures
