**The task**

The Client is a steel plant. In order to optimize the production costs, the Client wants to reduce electricity consumption at the stage of steel processing.

The task is to predict steel melting temperature. The quality is mearured by `MAE`. In best case scenario the value on the test sample should not exceed 6 degrees (Celsius).

**Data**

Data about different stages of steel processing process.

 - `data_arc` - data on electrodes;
 - `data_bulk` - data on adding of bulk materials;
 - `data_bulk_time` - data on time of adding of bulk materials;
 - `data_gas` - data on gas purge;
 - `data_temp` - data on temperature measurements;
 - `data_wire` - data on adding of wire materials;
 - `data_wire_time` - data on time of adding of wire materials.
 
**Libraries used**

pandas <br/>
matplotlib <br/>
seaborn <br/>
sklearn <br/>
catboost <br/>
lightgbm
