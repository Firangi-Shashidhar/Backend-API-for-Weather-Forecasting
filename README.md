# Backend-API-for-Weather-Forecasting

Weather API with Flask:
This project implements a simple weather API using Flask, allowing users to retrieve current weather information for multiple locations. The weather data is fetched from the OpenWeatherMap API.

Prerequisites:

Python

Flask

Requests library


Brief Procedure:
1.	Install the required libraries.
2.	Get your OpenWeatherMap API key.
3.	Run the application.
4.	Open Postman and create a new request to http://127.0.0.1:5000/weather with the GET method.
5.	Add a query param location with the value being the city and state (eg: Bengaluru, KA).
6.	Send the request and check the output.
7.	NOTE: You can check the accuracy of the retrieved weather data by OpenWeatherMap.

   
Detailed explanation:
1.	Run the python script in VScode
2.	In the terminal you can see the base url http://127.0.0.1:5000. When you click on this url, you will see 404 error.
3.	Now go to your Postman workspace, set the request type to GET.
4.	Enter the URL for your Flask API endpoint i.e, http://127.0.0.1:5000/weather?.
5.	Click on the “Params” tab. In the “Key” column, enter location. In the “Value” column, enter the city and state for which you want to retrieve the weather information.
6.	Click the send button to make the request.
7.	Now go back to the base url, inorder to fetch the weather data, you have to append the base url with the api endpoint i.e, http://127.0.0.1:5000/weather?location=city,state(eg: http://127.0.0.1:5000/weather?location=Bengaluru,Karnataka&location=Mysore, Karnataka).
8.	Now you can see the json file.




