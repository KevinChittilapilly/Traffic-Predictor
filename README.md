# Traffic-Predictor

At the broad level, a smart city is a recognition/ designation/ identification given by the authority to a city, that incorporates information and communication technologies (ICT) to enhance the quality of living in an urban setup. Through the usage of smart technology a smart city is empowered with enhanced quality and performance in energy, transportation, utilities, waste management, daily living etc for its citizens.



Simply put smart cities are meant to improve the quality of urban life. Intelligent Transportation System (ITS) is an important part of smart cities. And one major challenge in transportation in an urban setup is its heavy traffic problem, which frequently leads to gridlock, commonly known as traffic congestion or traffic jam. This problem can be addressed in two ways. 

By improving the traffic management system, constantly monitoring the traffic situation, planning-replanning the routes and constantly communicating the situation. This management type can be termed as a reactive management of traffic. This is ‘operation and resource heavy’ and adds hugely to operational cost.
A smarter way to handle this situation in a smart city would be predicting the traffic flow in the city using machine learning/ deep learning techniques and take preemptive measures. 


Today, our topic of discussion is building a traffic forecaster that can predict the traffic flow in a smart city accurately and in real-time. 



An impact of the growth in urbanization is rapidly growing number of vehicles in the cities. This leads to increase cost generated from traffic congestion in the urban setup. Traffic congestion means delay in service, lesser number of services, wastege of fuel, air and sound polution and overall loss of morale of citizens. Accurate and real-time traffic flow prediction is an unavoidable part of Intelligent Transportation System, especially for traffic control.



In the following sections we will learn about building a traffic forecaster model applying several machine learning/ deep learning techniques. 



Time series analysis based models such as ARMA, ARIMA are mainly linear models and cannot describe the stochastic and nonlinear nature of traffic flow. In recent years, deep learning based methods have been devised as alternatives for traffic flow prediction. We have used Long Short-Term Memory (LSTM) method to predict short-term traffic flow. Before we proceed further, this is recommended that you go through the LSTM session and refresh your learning.



Let us first clearly state our objective. 

Building a traffic forecaster that can predict the traffic flow in a smart city accurately and in real-time.


We will now take a dataset and go on applying several techniques step by step on the dataset to explain how traffic forecaster model is devised.



The dataset consists of total traffic volume of a particular road crossing for every one-hour interval for few month of year 2013. For any day, there are 24 sequential data points. The dataset consists of 6 columns. ‘yr’ column denotes the year, ‘month’ column denotes month. Month equals to 1 means January month and 2 mean February and so on. The ‘day’ column denotes day of the month starting from 1 up to 31. 'weekday' column denotes day of the week, Monday, Tuesday and so on. The ‘hr’ columns divides a day in to 24 intervals. For example, ‘hr’ equals to 8 means the interval 7 am to 8 am. And finally, traffic_valume denotes total flow of cars in this one-hour time interval.

