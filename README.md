INTRODUCTION-
Transport demand forecasting is to predict future transport demand when establishing transport plans within a given budget Transport demand is a quantitative input to evaluate supply strategy of transport facilities and land use planning. Presented as travel volume based on transport system usage, including transport facilities and transport services. The derived demand was created by continuous interaction of transport systems and activity systems
Description of the data
train_revised.csv (zipped) is the dataset of tickets purchased from Mobiticket for the 14 routes from “up country” into Nairobi between 17 October 2017 and 20 April 2018. This dataset includes the variables: ride_id, seat_number, payment_method, payment_receipt, travel_date, travel_time, travel_from, travel_to, car_type, max_capacity.

test_questions.csv is the dataset on which you will apply your model to estimate number of tickets sold by Mobiticket per unique ride. This dataset contains all of the rides offered on the same 14 routes during the two weeks following train.csv, i.e. 21 April 2018 to 9 May 2018. The variables included in this dataset: ride_id, travel_date, travel_time, travel_from, travel_to, car_type, max_capacity.

sample_submission.csv is a table to provide an example of what your submission file should look like. This table has two columns: ride_id, number_of_ticket.

Uber Movement traffic data can be accessed at movement.uber.com. Data is available for Nairobi through June 2018. (If the data for April-June are not up yet, they will be shortly.) Uber Movement provided historic hourly travel time between any two points in Nairobi. Any tables that are extracted from the Uber Movement platform can be used in your model.
