# Car-Insurance
 
The stake holder is the insurance company

The dataset is sourced from https://www.kaggle.com/datasets/sagnik1511/car-insurance-data

DESCRIPTION

This involves Car Insurance data set that is about the annual insurance data of a company

The outcome column indicates 1 if a customer has claimed his/her loan else 0.

The data has 19 features from there 18 of them are corresponding logs which were taken by the company.

ANALYTICAL INSIGHTS

![Vehicle type vs outcome visualization](https://github.com/Tendo4/Car-Insurance/assets/22962828/890843e0-29c3-4ef3-acdf-746232e3ea86)


The above visual shows us that people who own sports cars are more likely to claim for insurance.
This could be due to the fact that sports cars are more likely to cause accidents because they are fast and move at high speeds and are more likely to cause accidents 


![Driving epirience vs outcome visualization](https://github.com/Tendo4/Car-Insurance/assets/22962828/a115e9bd-7b56-4a0d-951e-5a44bf9e89b6)


The above visual shows us that as the drivers expirience increases , the outcome reduces .
This means that more expirienced drivers are less likely to make insurance claims 

I selected the KNN model 

Its metrics are shown below

recall:0.88

precision:0.69

accuracy:0.86

Explanation of false positive and false negative  impact on stake Holders

False positives :213

False negatives :244

Basing on the above information , this means that the insurance company isnt able to 100% find out the information about the outcome of people who applied for insurance and those that didnt 

RECOMMENDATIONS:

1) I recommend that Insurance packages should be issued more to people who drive sedan car types because the rate at which they make claims is lower than that of those who drive sports cars          

2) People with a longer driving experience should be targeted and issued insurance because they hardly claim for insurance



