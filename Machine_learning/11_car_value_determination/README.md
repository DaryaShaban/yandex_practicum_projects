**The task**

The Client is a used cars sale service, which needs to develop an application, where its customers may determine the value of their used cars (potential price to offer) based on the number of car characterisctics. 

The Client focuses on three aspects:
- quality of the prediction;
- speed of the prediction;
- model learning time.

The quality is mearured by `RMSE` - root-mean-square deviation between the target and the prediction.

**Data**

Historical data: technical specifications, equipment and prices of cars.

 - `DateCrawled` - date of downloading the questionnaire from the database;
 - `VehicleType` - type of car body;
 - `RegistrationYear` - year of vehicle registration;
 - `Gearbox` - type of gearbox;
 - `Power` - power (in hourse powers);
 - `Model` - car model;
 - `Kilometer` - mileage (km);
 - `RegistrationMonth` - month of car registration;
 - `FuelType` - type of fuel;
 - `Brand` - car brand;
 - `NotRepaired` - was the car under repair or not;
 - `DateCreated` - date of creation of the questionnaire;
 - `NumberOfPictures` - the number of photos of the car;
 - `PostalCode` - postal code of the owner of the profile (user);
 - `LastSeen` - date of last user activity.

Target feature
 - `Price` - price (euro).

 
**Libraries used**

pandas <br/>
numpy <br/>
seaborn <br/>
matplotlib <br/>
math <br/>
sklearn <br/>
catboost <br/>
lightgbm
