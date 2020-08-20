# experimentation_uplift_testing
### Introduction 
Form Feb 2019 to April 2019, Chip's location has been changed for three trail store 77, 86, 88. Goal of the project is to find out the control store and trail store with control store based on below three matrics.
* Monthly sales of the store
* Monthly average number of customer
* Average transaction per customer 

### Requirement 

* pandas
* numpy
* Matplotlib
* Seaborn

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, 
which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.

### Code
Template code is provided in the `Task2_experimentation_uplift_testing.ipynb ` jupyter notebook file. 
You will also be required to use the `QVI_data.csv`dataset file to complete your work. 

### Challenges 
Find out control store which has same behavior as a trail store during June2018 to Jan 2019.

### Result 
After carefully reviewing heatmap correlation and absolute distance over 3 matrices, following control stores have been selected.
`Control stores`: 157,229,233 <br><br>
<strong> Monthly sales comparision of trail store and control store during Trail period </strong><br>
<img src="https://github.com/salehas222/experimentation_uplift_testing/blob/master/images/Capture.PNG">
<br>
<strong>Monthly number of customer for trail store and control store during Trail period</strong> <br>

<img src="https://github.com/salehas222/experimentation_uplift_testing/blob/master/images/Capture1.PNG">
<br>
<strong> Monthly avg. transcation per customer </strong>
<img src="https://github.com/salehas222/experimentation_uplift_testing/blob/master/images/Capture2.PNG">
  
### Conclusion

<strong>Trail Store 77 - Positive</strong>

Monthly sale was increased from 235 to 243.5 Dollars
No of customer was increased by two. At the starting of the Feb. No. of customer was 45
intially no. of tx per customer was 1 which was increased to 1.02

<strong>Trail Store 86 - Negative</strong>

Monthly sale was decreased from 913.2 to 848.2 Dollars
No of customer was decreased by nine. At the starting of the Feb. No. of customer was 139
intially no. of tx per customer was 1.29 which was increased to 1.20

<strong>Trail Store 88 - Positive<strong>

Monthly sale was increased by 69 Dollars Which was the highest among all the trail store
No of customer was increased 154 to 162
no. of tx per customer increased sligtly.

In conclusion, Change in the location of chips has positive impact on trail store 77 and 88,but having negative impact on 86 store
