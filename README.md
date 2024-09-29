### Date created
I have created this project in 18 March 2021 and add README file in 24 March 2021.

### Project Title
Exploring US Bike Share Data

### Description
In this project, I used Python to explore data related to bike share systems for three major cities in the United States Chicago, New York City, and Washington. I wrote a code to import the data and answer interesting questions about it by computing descriptive statistics. Besides, I did include a script that takes in raw input to create an interactive experience in the terminal to present these statistics.

### Purpose of the project
We have learned about bike share usage in Chicago, New York City, and Washington by computing a variety of descriptive statistics. In this project, I wrote code to provide the following information:
1. Popular times of travel (i.e., occurs most often in the start time)
- most common month
- most common day of week
- most common hour of day

2. Popular stations and trip
- most common start station
- most common end station
- most common trip from start to end (i.e., most frequent combination of start station and end station)

3. Trip duration
- total travel time
- average travel time

4. User info
- counts of each user type
- counts of each gender (only available for NYC and Chicago)
- earliest, most recent, most common year of birth (only available for NYC and Chicago)

### Files used
In this project, I used data provided by [Motivate](https://www.motivateco.com/), a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

- Start Time (e.g., 2017-01-01 00:07:57)
- End Time (e.g., 2017-01-01 00:20:53)
- Trip Duration (in seconds - e.g., 776)
- Start Station (e.g., Broadway & Barry Ave)
- End Station (e.g., Sedgwick St & North Ave)
- User Type (Subscriber or Customer)
- Gender (only in Chicago and New York City)
- Birth Year (only in Chicago and New York City)

The original files are much larger and messier, and you don't need to download them, but they can be accessed here if you'd like to see them ([Chicago](https://www.divvybikes.com/system-data), [New York City](https://www.citibikenyc.com/system-data), [Washington](https://www.capitalbikeshare.com/system-data)). These files had more columns and they differed in format in many cases. Some data wrangling has been performed to condense these files to the above core six columns to make my analysis more straightforward.

### Software requirements
- You should have Python 3, NumPy, pandas, and tabulate installed using Anaconda
- A text editor, like Sublime or Atom.
- A terminal application (Terminal on Mac and Linux or Cygwin on Windows).


### Credits
- [Udacity](https://www.udacity.com/)
- [Motivate](https://www.motivateco.com/)
- [capitalbikeshare](https://www.capitalbikeshare.com/system-data)
- [citybikenyc](https://www.citibikenyc.com/system-data)
