This is a Python project that analyses the 911 calls data from Kaggle. The goal of this project is to better understand the distribution of 
emergency calls made to 911, as well as the reasons behind these calls.


To run this project, you will need the following software installed on your machine:

Python 3.x
Jupyter Notebook
Pandas
Matplotlib
Seaborn

**Dataset**
The dataset used in this project was obtained from Kaggle and contains information on emergency calls made to 911 in Montgomery County, PA. 
The data includes the following fields:

- lat: String variable, Latitude
- lng: String variable, Longitude
- desc: String variable, Description of the Emergency Call
- zip: String variable, Zipcode
- title: String variable, Title
- timeStamp: String variable, YYYY-MM-DD HH:MM:SS
- twp: String variable, Township
- addr: String variable, Address
- e: String variable, Dummy variable (always 1)

**Analysis**
In the Jupyter Notebook, the data is loaded into a Pandas DataFrame and then cleaned and transformed to make it easier to work with. 

The following steps are performed:

- Removing duplicates
- Parsing dates and creating new columns for year, month, day, hour, and minute
- Creating new columns for day of the week, and whether the call was made during the day or at night
- Grouping the data by the reason for the emergency call
- Finally, the data is visualized using Matplotlib and Seaborn to better understand the distribution of emergency calls and the reasons behind them.

