**The task**

The Client is a chain of supermarkets, that introduces a computer vision system for customers' photos processing. 
Photo fixation in the checkout area will help determine the age of customers in order to solve a number of challenges the stores have. The task is to build a model that determines the age of a person from a photo.

The quality is mearured by `MAE` metrics. The value on the test sample should not exceed 8.

**Data**

Data includes photos, as well as a file with markup on the age of people from the photos:

 - `file_name` - photo title;
 - `real_age` - age of the person.
 
**Libraries used**

pandas <br/>
numpy <br/>
matplotlib <br/>
seaborn <br/>
tensorflow (keras)

**Status**

finished
