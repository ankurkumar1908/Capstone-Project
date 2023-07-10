# Capstone-Project
Used Car Price Prediction Problem

**Introduction to the Problem:**
A used car is a pre-owned or second hand vehicle, which is repaired and refurbished to regain 
working conditions before the sale. The prices of new cars in the industry is fixed by the 
manufacturer with some additional costs incurred by the Government in the form of taxes. So, 
customers buying a new car can be assured of the money they invest to be worthy. But due to the 
increased price of new cars and the incapability of customers to buy new cars due to the lack of 
funds, used cars sales are on a global increase. There is a need for a used car price prediction 
system to effectively determine the worthiness of the car using a variety of features. Even though 
there are websites that offers this service, their prediction method may not be the best. Besides, 
different models and systems may contribute on predicting power for a used car’s actual market 
value. It is important to know their actual market value while both buying and selling.

**Problem Statement:**
Predicting price of used car affected by several factors including mileage, manufacturer, model, 
year, etc.

**Abstract:**
Determining the listing price of a used car is a challenging task, due to the many factors that 
affect a used vehicle’s price in the market. Major focus of this project is to develop a machine 
learning model that can accurately predict the price of a used car based on its features. This model 
will be useful to businesses involved in retail of such vehicles. We will implement and evaluate 
various learning methods on the dataset.

**Variable Identification:**
**Independent:** Id, URL, Region, Region URL, Year, Manufacturer, Model, Condition, 
Cylinders, Fuel, Odometer, Title Status, Transmission, VIN, Drive, Size, Type, 
Paint color, Image URL, Description, State, Lat, Long, Posting Date.
**Target** : Price

**Variable Information:**
• Price : Price of the used cars (Estimated price of the car listed by the seller)
• Id : This column tells us about the unique ID for each unique category/row.
• URL : This columns tells us about the unique URL for each listings with complete 
details.
• Region : Region of where the car is from.
• Region URL : URL of a specific region of the listing of the car.
• Year : In which year the car was purchased 
• Manufacturer : This column consist of Company names the car belongs to.
• Model : Name of the car.
• Condition : The condition in which the car is kept.
• Cylinders : No of cylinders present in the car.
• Fuel : The kind of fuel on which the car operates.
• Odometer : Number of miles travelled by the car’s previous owner(Distance that car 
has travelled).
• Title Status : Current Status of vehicles.
• Transmission : Mode of power transfer in a vehicle (automatic/manual etc).
• VIN : Unique Vehicle identification number.
• Drive : Type of drive (rear wheel drive, front wheel drive, 4 wheel drive).
• Size : Segment of the car(6seater/4seater, etc).
• Type : Type of the vehicle.
• Paint Color : Colour of the car.
• Image URL : This column shares the links where we can see the images of the cars.
• Description : Detailed description of the condition of the car.
• County : This column has all values as Nan so we will drop this column.
• State : In which area the car is situated.
• Lat : Latitudinal position of the car.
• Long : Longitudinal Position of the car.
• Posting Date : Date of posting of the ad
