# Challenge-12

## Credit Risk

The purpose of this analysis was to use customer information to determine if a loan was healthy or unhealthy for a peer to peer lending company

Step 1: Import the lending data CSV 

Step 2: Create two variables X and y with the CSV data, with the binary data of loan status occupying variable y and everything in variable X

![X and y](Images/X and y.jpg)

Step 3: Use the LinearRegression model from sklearn on the data 

Step 4: Add resampling data using RandomOverSampler 

Step 5: Create a Report explaining the findings and what model worked the best 




---

## Technologies
This application is written in Python 3.7  

this application uses the following packages:
 
pandas

numpy 

sklearn

imblearn

pathlib

---

## Installation Guide

Before running the application first install the following dependencies.
See the associated Screenshot for what to Install 

![imports](Images/imports .jpg)

![imports 2](Images/imports 2.jpg)

![import 3](Images/import 3.jpg)

![imports 3](Images/imports 3.jpg)


---

## Examples

Please see the following images of the code 

The first set of data we looked at 

![target balance](Images/target balance.jpg)



Results of the first Linear Regression 

![results](Images/imports 3.jpg)

The data after applying the RandomOverSampler

![rebalanced targets ](Images/rebalanced targets.jpg)

The results from that linear regression

![resampled results ](Images/resampled results.jpg)



---

## Usage

To use the data simply clone the repository.

Different sales values can be imput and the projections will change as well 

Charts could also be changed to make things look different  
```
---

## Contributors

Sean Patel (myself) seanpatel076@gmail.com
---

## License

License is public anyone can use or make changes to this application