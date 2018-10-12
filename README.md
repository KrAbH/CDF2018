# CFD2018
Predicting natural hazards and management.
It is not too long when cyclone "Titli" hit the parts of India and caused too much damage. Now a days quite frequently we are seeing
having this kind of occurences like recent flood in Kerala, Hurricane Michael striking US. These kind of natural disasters effects way too
many lives and destroys huge infrastructure. A pre warining before the disaster can save lots of lives. Organized and efficient 
distribution of rescue can also save lots of life. We want to address the problem of proper management in rescue operations to save maximum lives. 

# Our Problem Statement
When a natural hazard occurs the amount of resources and number of personnel to help is quite limited. We want to address this issue 
by creating a mechanism such that it deploys the manpower and resources such that it maximizes the help to the victims. 

# Our Solution
We are proposing a solution based using techniques of machine learning and Optimization methods to effectively provide the help to the victims
in a very efficient way.

## Part 1: Finding the locations 
This Part uses machine learning techiniques to learn/define a pre disaster model depending on the information of the public residential spaces
, there daily movements or any such feature on which the the location of the victims can be prediceted precisely. As it quiet uncertatin where is the population currently 
present when the disaster happened , so if we pretain a network/model to find these locations where we have to send the help , it could save 
many lives.

## Part 2: Sending the aid
We answer the problem of sending the resources and monpower in an effective manner by formulate this as an optimisation problem as : 
we know the constraints (as in Optimisation Problem) giving how much and what resources are required at the different locations 
(can be variable X in Optimization Problem) and from which help camp (Y variable in the Optimizaton Problem) we have to send the required 
resources , with the help of our machine learning model. We have to minimize the time (decision variable in our Optimisation Problem) to 
provide the aid to the victims as quicly as possible.

# Uncertainties our solution will answer
1. If we get any new locations of the victims ( with their requirements) or any new help camps (with their sources) , our solution will handle this
situation effectively.
2. Our machine learning model will be able to add any new feature, on which the predition of the location of the victims depends, effectively to 
the system.
