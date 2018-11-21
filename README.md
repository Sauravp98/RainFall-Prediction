# RainFall-Prediction

Team Members:-Saurav Panda,Uttaran Tribedi,Sarthak Sahai.

Abstract/Goal:-
         We are trying to built a Rainfall prediction model that will take different sets of data as  input from sensors using       microcontroller(arduino) and then with those parameters categorise the rainfall(precipitation) into 4 categories. [No Rain,Drizzle,Moderate and Heavy]. In our case we also generate the precipitation values ,in which "heavy" with some modifications would mean that the precipitation can cause a flood and  accordingly modifying the "no rain" condition(for prolonged periods) would mean condition of drought. (Both flood and draughts hereby being "Natural Disasters"). We can therefore issue alerts to people living in such places and warn them about such disasters about to occur in near future and hence take all possible steps to save lives.
      The Model is trained with Logistic Regression algorithm and uses the austin weather dataset and boston weather dataset( we are still trying to search for data relevant to Indian Weather) from kaggel and gives an accuracy of approximately 75% on training set and 74% on the test set. Data from the arduino will be stored to a csv file which will then be used by the trained python script to give prediction.
