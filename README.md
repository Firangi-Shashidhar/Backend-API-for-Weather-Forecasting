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


output Screenshots:

![Screenshot 2023-11-28 122519](https://github.com/Firangi-Shashidhar/Backend-API-for-Weather-Forecasting/assets/136114163/d805d287-5d89-43b7-bc07-449c1721cc9a)

![Screenshot 2023-11-28 132702](https://github.com/Firangi-Shashidhar/Backend-API-for-Weather-Forecasting/assets/136114163/6cbfcce9-13f1-4c4c-8287-309236c8624f)

![Screenshot 2023-11-28 132730](https://github.com/Firangi-Shashidhar/Backend-API-for-Weather-Forecasting/assets/136114163/2492f765-9669-4055-b804-2e21748fa9b6)

![Screenshot 2023-11-28 133043](https://github.com/Firangi-Shashidhar/Backend-API-for-Weather-Forecasting/assets/136114163/58115228-365a-4b47-96a9-8ffb13dd5e6c)

![Screenshot 2023-11-28 133055](https://github.com/Firangi-Shashidhar/Backend-API-for-Weather-Forecasting/assets/136114163/75acb6eb-eaa1-4002-b2c6-5499ab77e968)


Additionals:


This python script accepts multiple query parameters. The code includes the ability to retrieve weather information for multiple locations through the /weather endpoint.

The code includes try-except blocks to catch and handle exceptions that may occur during API requests or data processing.

Appropriate status codes are returned in the API responses, such as 400 for bad requests, 200 for response and 500 for internal server errors.









