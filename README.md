# Project Title: US Bikeshare Data Analysis

### Date Created
September 05, 2024

### Project Title
Bikeshare Data Analysis

### Description
This project involves analyzing bikeshare data from various cities to gain insights into travel patterns. The analysis is performed using a Python script that processes and visualizes data from CSV files containing bikeshare trip information.

### Files used
#### CSV Files

#### `chicago.csv`
- **Description:** Contains bikeshare trip data for Chicago.
- **Columns:**
  - `Start Time`: The start time of the trip.
  - `End Time`: The end time of the trip.
  - `Trip Duration`: Duration of the trip in seconds.
  - `Start Station`: The starting station of the trip.
  - `End Station`: The ending station of the trip.
  - `User Type`: The type of user (e.g., Subscriber, Customer).
  - `Gender`: Gender of the user (optional, may not be present in all datasets).
  - `Birth Year`: Birth year of the user (optional, may not be present in all datasets).

#### `new_york_city.csv`
- **Description:** Contains bikeshare trip data for New York City.
- **Columns:**
  - `Start Time`: The start time of the trip.
  - `End Time`: The end time of the trip.
  - `Trip Duration`: Duration of the trip in seconds.
  - `Start Station`: The starting station of the trip.
  - `End Station`: The ending station of the trip.
  - `User Type`: The type of user (e.g., Subscriber, Customer).
  - `Gender`: Gender of the user (optional, may not be present in all datasets).
  - `Birth Year`: Birth year of the user (optional, may not be present in all datasets).

#### `washington.csv`
- **Description:** Contains bikeshare trip data for Washington D.C.
- **Columns:**
  - `Start Time`: The start time of the trip.
  - `End Time`: The end time of the trip.
  - `Trip Duration`: Duration of the trip in seconds.
  - `Start Station`: The starting station of the trip.
  - `End Station`: The ending station of the trip.
  - `User Type`: The type of user (e.g., Subscriber, Customer).
  - `Gender`: Gender of the user (optional, may not be present in all datasets).
  - `Birth Year`: Birth year of the user (optional, may not be present in all datasets).

#### Python Script

#### `bikeshare_analysis.py`

This Python script performs an analysis of bikeshare data. It includes functions to:
- Get user input for city, month, and day to filter the data.
- Load the data for the specified city and apply filters.
- Display statistics on the most frequent times of travel.
- Display statistics on the most popular stations and trips.
- Display statistics on trip duration.
- Display statistics on bikeshare users.

##### Functions

- **`get_filters()`**: Asks the user to specify a city, month, and day to analyze.
- **`load_data(city, month, day)`**: Loads and filters data based on the city, month, and day provided.
- **`time_stats(df)`**: Displays statistics on the most frequent times of travel.
- **`station_stats(df)`**: Displays statistics on the most popular stations and trips.
- **`trip_duration_stats(df)`**: Displays statistics on the total and average trip duration.
- **`user_stats(df)`**: Displays statistics on bikeshare users.

### Credits
This project was inspired by the Bikeshare project from the Udacity Data Analyst Nanodegree. Special thanks to the following resources:

- [Udacity's Data Analyst Nanodegree GitHub Repository](https://github.com/udacity/pdsnd_github)
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [Python Documentation](https://docs.python.org/3/)
