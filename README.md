# Predicting the Cost of Plane Tickets

The cost of plane tickets can be difficult to pin down. A great deal one day may increase its price substantially the next. Alternatively high priced tickets may appear to spontaneously drop without a clear cause.

In this analysis I looked into the various features that most affect the cost of plane ticket and built a model to minimize mean squared error. 

The dataset contains the following features:  

   * Airline - str, name of operating airline  
   * Date-of-Journey - datetime, date of departure  
   * Source - str, name of city flight departs from  
   * Destination - str, destination city  
   * Route - str, string of cities that flights passes through  
   * Dep_Time - timestamp, time of departure  
   * Arrival_Tiem - timestamp, time of arrival  
   * Duration - timedifference, length of flight in hh:mm  
   * Stops - str, number of stops in flight journey (0, 2]  
   * Additional_Info - str, categorical data including info on in flight amenities, etc  
   * Price - int, dependendent variable, cost of flight  
    
Training set contains 10683 rows, test set contains 2671 rows.

This project was part of a machine learning competition hosted by MachineHack.com
