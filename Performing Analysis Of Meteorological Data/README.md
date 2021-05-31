# Let us understand what is Meteorology: 

"Meteorology is a branch of the atmospheric sciences which includes atmospheric chemistry
and atmospheric physics, with a major focus on weather forecasting. For more knowledge
refer [link text itself](https://en.wikipedia.org/wiki/Meteorology)". 

You can find the data set on Kaggle [Dataset] (https://www.kaggle.com/muthuj7/weather-
dataset). We are going to use NumPy, Pandas, and Matplotlib of Python to import, extract,
clean, transform and plot.

**Hypothesis:** Has the Apparent temperature and humidity compared monthly across 10 years
of the data indicate an increase due to Global warming?

**Step 1- Let's start by importing libraries:** To make use of the functions in a module,
you'll need to import the module with an import statement. An import statement is made up
of the import keyword along with the name of the module. Example: import numpy.

**Step 2- Reading dataset:** A dataset is a collection of data. In the case of tabular data, a 
dataset corresponds to one or more database tables, where every column of a table
represents a particular variable, and each row corresponds to a given record of the dataset in
question. In this scenario, we are going to read weather History.csv as our dataset.

**Step 3- Cleaning dataset:** Data cleaning is the process of fixing or removing incorrect,
corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset. Dropping
unwanted data and converting it according to our requirements.

> **NOTE:** We need to analyze data yearly. We need to convert Formatted Date into 
DateTime format. We will do it by using the Pandas method to_datetime(). Also, 
we will set Formatted Date as the index to the dataset and resample our data.

**Step 4- Plotting of Data:** The purpose of plotting data is to visualize variation or show
relationships between variables. We will now plot the line graph to display Humidity and
Apparent Temperature(C) over 10 years(2006–2016). We will plot the graph to display the
average temperature and humidity for 12 months over the 10 year period.

## Conclusion

As we can analyze there isn’t any change in humidity in the past 10 years(2006–2010) for
the month of January. whereas temperature increases sharply in 2009 and drops in 2015 for
the rest of the years there isn’t any sharp change in the temperature.

I am thankful to mentors at [link text itself](https://internship.suvenconsultants.com) for providing awesome
problem statements and giving many of us a Coding Internship Experience. Thank you
[link text itself] (www.suvenconsultants.com)


> **Note:** This conclusion statement is for only the month of January, please refer to
the model for all the months.
