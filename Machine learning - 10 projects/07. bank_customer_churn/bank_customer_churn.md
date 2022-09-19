**The task**

The Client is Beta-Bank. The Client faced an issue with customers leaving the bank: monthly, a little, but noticeable. As it is cheaper to keep the current customers than to attract new ones, the bank would like to build a model, that predicts whether a customer will leave the bank in the near future or not. 

The model metrics will be `F1-measure`. The metric must be at least `0.59`. Additionally, the AUC-ROC measure in comparison with the F1-measure should be evaluated.

**Data**

Historical data on customer behavior and termination of agreements with the bank.

 - `RowNumber` - row index in data
 - `CustomerId` - unique customer identifier
 - `Surname` - surname
 - `CreditScore` - credit rating
 - `Geography` - country of residence
 - `Gender` - gender
 - `Age` - age
 - `Tenure` - how many years a person has been a bank client
 - `Balance` - account balance
 - `NumOfProducts` - the number of bank products used by the client
 - `HasCrCard` - the presence of a credit card
 - `IsActiveMember` - client activity
 - `EstimatedSalary` - estimated salary
 - `Exited` - the fact that the client left (**target**)
 
**Libraries used**

pandas <br/>
numpy <br/>
seaborn <br/>
sklearn <br/>
matplotlib
