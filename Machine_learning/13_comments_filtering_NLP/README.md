**The task**

The Client is an online store, that launches a new service, where users can edit and supplement product descriptions. The store needs a tool that will look up for the toxic comments and submit them for the moderation.
The task is to train the model which will classify comments into positive and negative. 

The quality is mearured by `F1` metrics. The value on the test sample should be at least 0.75.

**Data**

Data with markup on the toxicity of comments

 - `text` - text of the commentary;
 - `toxic` - whether the commentary is toxic or not (1 - toxic/negative, 0 - positive).
 
**Libraries used**

pandas <br/>
matplotlib <br/>
re <br/>
nltk <br/>
sklearn <br/>
catboost <br/>
lightgbm

**Status**

finished
