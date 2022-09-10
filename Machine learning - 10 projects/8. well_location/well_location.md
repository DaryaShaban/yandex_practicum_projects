**The task**

The client is a mining company. It set a task to decide where to drill a new well.

The subtasks include creation of a model to determine the region where mining will bring in the most profit + analyze possible profits and risks using the Bootstrap technique (Average Profit, 95% Confidence Interval and Risk of Losses).

More precise and specific task conditions are described in `ipynb` file.

**Data**

The data is data on oil samples in three regions: there are 10,000 oilfields in each, the quality of oil and the volume of its reserves have been measured. 

 - `id` is the unique identifier of the well;
 - `f0`, `f1`, `f2` - three parameters of wells (for the purpose of the task it is irrelevant what they mean, the features themselves are significant);
 - `product` is the volume of the reserves in the well (in thousand barrels).

**Libraries used**

pandas <br/>
numpy <br/>
seaborn <br/>
sklearn
