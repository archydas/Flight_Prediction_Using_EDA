# Flight_Prediction_Using_EDA
## Flight Price Prediction Using EDA
## Project Overview
This project aims to predict flight ticket prices based on various factors such as airline, departure time, arrival time, duration, and number of stops. By analyzing historical flight data using Exploratory Data Analysis (EDA) and machine learning techniques, this project seeks to build a model that can accurately forecast flight prices, providing a useful tool for passengers and travel businesses to understand pricing trends and make informed decisions.
## Objective
The primary goal of this project is to develop a predictive model that can estimate flight prices based on key features. This can help users identify the best times to book flights and understand how factors like the date of booking and travel duration influence the price.
## Dataset
The dataset used for this project contains information about flights, including:
a. Airline: The airline providing the service.//
b. Date of Journey: The departure date of the flight.
c. Source and Destination: Cities where the flight departs from and arrives.
d. Route: The flight route with possible layovers.
e. Departure and Arrival Time: Times of departure and arrival.
f. Duration: Total flight duration.
g. Total Stops: Number of stops in the flight journey.
h. Price: The ticket price (target variable for prediction).
## Workflow
## 1. Data Cleaning and  Preprocessing
   a. Handling Missing Data: Missing values were filled or removed as appropriate.
   b. Date/Time Features: Date-related features like "Date of Journey", "Departure Time", and 
      "Arrival Time" were transformed into useful formats such as day, month, hour, and minute.
   c. Categorical/ Feature  Encoding: Categorical features like Airline, Source, and 
      Destination were encoded using one-hot encoding to convert them into numerical formats.
   d. Feature Engineering: Additional features like total travel time and whether a flight 
      departs during peak hours were created to capture the complexities of flight pricing.
## 2. Exploratory Data Analysis(EDA)
   EDA was performed to understand the relationship between flight prices and the various 
   features. Key insights include:
     a. Airlines: Certain airlines have consistently higher or lower ticket prices.
     b. Flight Duration: Longer flights generally have higher ticket prices.
     c. Stops: Non-stop flights tend to have higher prices, while flights with multiple stops 
        tend to be cheaper.
     d. Departure/Arrival Times: Flights during certain times of the day (e.g., early morning)          tend to have lower prices compared to peak hours.
## Results
The predictive model was able to achieve a high R² score and relatively low MAE and RMSE values, indicating good performance in predicting flight prices.
The most important factors influencing price were the airline, total duration of the flight, and the number of stops.
## Technologies and Tools
   a. Python: The core programming language used.
   b. Pandas and NumPy: For data manipulation and analysis.
   c. Matplotlib and Seaborn: For data visualization and exploratory data analysis.
   d. Scikit-learn: For machine learning model building and evaluation.
## Conclusion
This project demonstrates how machine learning and exploratory data analysis can be used to predict flight prices accurately. By analyzing key features and building predictive models, it provides valuable insights that can assist travelers and businesses in making better flight booking decisions.
## Future Improvements
1. Implement a real-time flight price tracker that predicts future prices based on new data.
2. Explore additional features such as passenger class and flight demand.
3. Deploy the model as a web application using frameworks like Flask or Streamlit for real-time predictions.
