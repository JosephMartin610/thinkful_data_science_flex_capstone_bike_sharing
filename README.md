# Thinkful Data Science Flex Course
# Experimental Design Capstone Project: Group Differences in a Rental Bike Sharing Dataset

**Introduction**

The data for this capstone project come from a rental bike sharing system in which riders pay to rent a simple bike for use on urban streets. Riders obtain a bike at one station, cycle, and then drop the bike off at another station. The data originally come from the Capital Bikeshare system in Washington, D.C. on all days in 2011 and 2012. According to Wikipedia, this was an early example of such a system in the United States. Capital Bikeshare launched in the later part of 2010, so these early data likely informed its ongoing growth.

One reason this dataset is of interest is because of the expanding use of these systems, as the creators point out: “There are about over 500 bike-sharing programs around the world which are composed of over 500 thousand bicycles.” There is great interest in these systems “due to their important role in traffic, environmental and health issues.”

The dataset creators aggregated counts of riders by hour (hour.csv) and day (day.csv). There are other columns related to various measures of time and weather. Using file day.csv, rider counts will be grouped according to these other columns to determine if there are significant differences among groups. Does the average count of riders depend on group classification by aspects of time or weather?

**Source Data**

The data were obtained from [Kaggle](https://www.kaggle.com/imakash3011/rental-bike-sharing) and originally come from the Capital Bikeshare system in Washington, D.C. on all days in 2011 and 2012.

In file day.csv, the dataset creators aggregated counts of riders by day. These counts are broken out into “casual” and “registered” users. Columns related to time are date, year, month, hour, season, day of the week, and whether the day is or is not a holiday or is or is not a working day. Weather-related columns added by the dataset creators from freemeteo.com are weather intensity, temperature, sensed temperature, humidity, and wind speed.

The data file is available [here](https://github.com/JosephMartin610/thinkful_data_science_flex_data_files/blob/main/day.csv) in another repository.

**Jupyter Notebook**

All of the code and results are in one Jupypter notebook, [supervised_learning_capstone_classification.ipynb](https://github.com/JosephMartin610/thinkful_data_science_flex_capstone_news_shares/blob/main/supervised_learning_capstone_classification.ipynb).

**Presentation**

The development and performance of the models are described here in the capstone [presentation](https://github.com/JosephMartin610/thinkful_data_science_flex_capstone_news_shares/blob/main/supervised_learning_capstone.pdf).
