# Udacty Sparkify project

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Files Description](#files)
4. [Result](#Result)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project uses the following software and Python libraries:

- Python
- Pyspark
- Pandas
- Matplotlib
- Seaborn

## Project Motivation<a name="motivation"></a>

The provided dataset contains behavior data from the music app "Sparkify". Pyspark will be used to analyse and predict churn rates of users depending on given features..

## Files Description<a name="files"></a>

**Sparkify .ipynb** Main file of the project, it demonstrates the process of using pyspark to explore the data and build the model. 
**mini_sparkify_event_data.json** sample data that was used.
**final_df_signle.parquet** if you want to skip most steps and just load the final df that was used for modeling, this is your pick.


## Result

According to the results of the model, it is the frequency of Thumbs Down that has the greatest impact. Churn users have more Thumbs Down. Naturally, users will leave if they are not satisfied.

I post a blog about the detail, you can find it [here](https://medium.com/@fxzero/how-to-predict-user-churn-using-pyspark-fe25f6de1d7a).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Udacity for the project. You can't use this for you Udacity capstone project. Otherwise, feel free to use the code here as you would like! 
