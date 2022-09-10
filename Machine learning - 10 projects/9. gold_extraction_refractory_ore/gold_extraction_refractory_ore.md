**The task**

The Client is a company, that develops solutions for the industrial enterprises. 
The task is to prepare a prototype machine learning model to avoid launching enterprises with unprofitable characteristics. 

The model should predict the recovery rate of gold from gold ore. 

The technological process includes flotation stage at which rougher concentrate is achieved. The next stage is gold refining (carried out in several iterations) to achieve the final concentrate.

The metrics for the model is `sMAPE` - Symmetric Mean Absolute Percentage Error.
The metrics is similar to `MAE`, but is expressed  in relative terms, not absolute. Symmetrical, as it equally takes into account the scale of both the target feature and the prediction.

The formula for final SMAPE is provided by the Client and considers errors in both stages of the gold extraction process:
**rougher stage** and **final stage**:

`Total sMAPE = 25% rougher sMAPE + 75% final sMAPE`

**Data**

Data with extraction and cleaning parameters.

Technological process
 - `Rougher feed` - feedstock
 - `Rougher additions (or reagent additions)` - flotation reagents: Xanthate, Sulphate, Depressant
 - `Xanthate` - xanthate (promoter, or flotation activator);
 - `Sulphate` - sulfate (in this production, sodium sulfide);
 - `Depressant` - depressant (sodium silicate).
 - `Rougher process`  - flotation
 - `Rougher tails`
 - `Float banks` - flotation unit
 - `Cleaner process` - cleaning/ refinement
 - `Rougher Au` - rough gold concentrate
 - `Final Au` - final gold concentrate

Stage parameters
 - `air amount` — air volume
 - `fluid levels` - fluid level
 - `feed size` - feed granule size
 - `feed rate` — feed rate


**Libraries used**

pandas <br/>
numpy <br/>
seaborn <br/>
matplotlib <br/>
sklearn
