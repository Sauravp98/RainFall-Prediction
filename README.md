# RainFall-Prediction
We are trying to built a Rainfall prediction model that will take data input from arduino uno using temparature,pressure and humidity sensors to get data and then with those parameter categorise the rainfall(precipitation) into 4 categories
[No Rain,Drizzle,Moderate and Heavy],in which the heavy would mean that the precipitation can cause a flood and using this we could issue alerts to warn people about it and take all possible steps to save lives.
The Model is trained with RandomForest algorithm and uses the austin weather dataset( we are still trying to search for data relevant to Indian Weather) from kaggel and gives an accuracy of approximately 96% on training set and 95% on the test set.
Data from the arduino will be stored to a csv file which will then be used by the trained python script to give prediction.
