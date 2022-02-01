# Surfs Up!

![surfs-up.png](Images/surfs-up.png)

I'm headed to Honolulu, Hawaii! To help me know what to pack for my trip, I did some climate analysis on the area.

## Climate Analysis and Exploration

I used Python and SQLAlchemy to do basic climate analysis and data exploration of your climate database. All of the following analysis were completed using SQLAlchemy ORM queries, Pandas, and Matplotlib.

### Precipitation Analysis

  ![precipitation](Images/precipitation.png)

### Station Analysis

    ![station-histogram](Images/station-histogram.png)

### Temperature Analysis I

* Hawaii is reputed to enjoy mild weather all year. Is there a meaningful difference between the temperature in, for example, June and December?

* Use pandas to perform this portion.

  * Convert the date column format from string to datetime.

  * Set the date column as the DataFrame index

  * Drop the date column

* Identify the average temperature in June at all stations across all available years in the dataset. Do the same for December temperature.

* Use the t-test to determine whether the difference in the means, if any, is statistically significant. Will you use a paired t-test, or an unpaired t-test? Why?

### Temperature Analysis II

    ![temperature](Images/temperature.png)

### Daily Temperature Normals

  ![daily-normals](Images/daily-normals.png)
