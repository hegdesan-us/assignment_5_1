# assignment_5_1
 Assignment 5.1 

 
 **URL:** https://github.com/hegdesan-us/assignment_5_1.git

**Name :** Sanjay Hegde \
**Couse :** UCB AI/ML 

**prompt_orig.ipynb :** Original Prompt file (Questions only)

**prompt_sol.ipynb :** Original Prompt file (Solutions)


**Directory :** Images \
  Description : Contains the images needed for the prompt questions and the Jupyter notebook 

**Directory : data** \
 Description : Contains the data file needed for the class project\
 Contains file : coupons.csv

### Summary of findings
 **Car cloumn is nor really needed. Missing significant information**

 ![MissingDataImage](images/missingdata.png)

 **Assumptions made to fill the missing data**
- Assuming that any NaN in Carryway means "less than 1" times people have ordered carry away
- Cleaned the values in Marital Status for easier processing later
- Number of times that he/she goes to a coffee house: for NaN assumes as less than 1
- Number of times that he/she eats at a restaurant with average expense less than $20 per person: Assuming never.
- Number of times that he/she eats at a restaurant with average expense between $20 to 50 per person: Assuming less than 1
- Number of times that he/she goes to a bar: Assuming never
- Car column doesn't contain enough data so dropping the column


**Coffee Store Coupon in Demand**

 ![MissingDataImage](images/coupon-distribution.png)
  
**Acceptance Rate by Bar Frequency**

 ![MissingDataImage](images/bar-acceptance.png)

**Is Morning and evening coupon usage is more?**

 ![MissingDataImage](images/hour-distribution.png)

**Unempoyed and students use coffee coupon more??**

 ![MissingDataImage](images/relation-coffee-coupon.png)

**Unempoyed and students use cheap resturent coupon more??**

 ![MissingDataImage](images/relation-coupon-cheapresturent.png)


 


 

 
