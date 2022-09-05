**The task**

The customer is Real Estate service. The customer has provided an archive of ads for the sale of apartments in St. Petersburg and neighboring settlements for several years. The task is to learn how to determine the market value of real estate: set the parameters, which will allow to build an automated system to track anomalies and fraudulent activity.


**Data**

Iput data is of two types: data entered by the user, data obtained automatically on the basis of cartographic data(like, the distance to the center, nearest park and etc).
Columns the dataset contains:
 - airports_nearest - distance to the nearest airport in meters (m)
 - balcony — number of balconies
 - ceiling_height - ceiling height (m)
 - cityCenters_nearest - distance to the city center (m)
 - days_exposition - how many days the ad was placed (from publication to withdrawal)
 - first_day_exposition - publication date
 - floor - floor
 - floors_total - total floors in the house
 - is_apartment - apartments (boolean)
 - kitchen_area - kitchen area in square meters (m²)
 - last_price - price at the time of unpublishing
 - living_area - living area in square meters (m²)
 - locality_name — name of the locality
 - open_plan - open plan (boolean)
 - parks_around3000 - number of parks within a 3 km radius
 - parks_nearest - distance to the nearest park (m)
 - ponds_around3000 - the number of ponds within a radius of 3 km
 - ponds_nearest — distance to the nearest body of water (m)
 - rooms - number of rooms
 - studio - studio apartment (boolean)
 - total_area - area of the apartment in square meters (m²)
 - total_images - the number of photos of the apartment in the ad

**Libraries used**

pandas <br/>
matplotlib <br/>
seaborn
