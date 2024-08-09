# Data Dictionary

## Activity DataFrame

- **Id**: Unique identifier for the user.
- **ActivityDate**: Date of recorded activity (MM/DD/YY).
- **TotalSteps**: Total number of steps taken.
- **TotalDistance**: Distance traveled in miles.
- **TrackerDistance**: Distance measured by the Fitbit tracker in miles.
- **LoggedActivitiesDistance**: Distance covered during logged activities in miles.
- **VeryActiveDistance**: Distance during very active periods in miles.
- **ModeratelyActiveDistance**: Distance during moderately active periods in miles.
- **LightActiveDistance**: Distance during light active periods in miles.
- **SedentaryActiveDistance**: Distance during sedentary periods in miles.
- **VeryActiveMinutes**: Minutes spent in very active periods.
- **FairlyActiveMinutes**: Minutes spent in fairly active periods.
- **LightlyActiveMinutes**: Minutes spent in lightly active periods.
- **SedentaryMinutes**: Minutes spent in sedentary periods.
- **Calories**: Total calories burned.

## Calories DataFrame

- **Id**: Unique identifier for the user.
- **ActivityHour**: Hour of the day when calorie data was recorded (MM/DD/YY HH:MM).
- **Calories**: Number of calories burned during the specified hour.

## Intensities DataFrame

- **Id**: Unique identifier for the user.
- **ActivityHour**: Hour of the day when intensity data was recorded (MM/DD/YY HH:MM).
- **TotalIntensity**: Total intensity score for the specified hour.
- **AverageIntensity**: Average intensity score for the specified hour.
- **Date**: Date of recorded intensity data (MM/DD/YY).
- **Hour**: Time of day for the recorded intensity data (HH:MM).

## Sleep DataFrame

- **Id**: Unique identifier for the user.
- **SleepDay**: Date and time of sleep data (MM/DD/YYYY HH:MM AM/PM).
- **TotalSleepRecords**: Total number of sleep records.
- **TotalMinutesAsleep**: Total minutes slept.
- **TotalTimeInBed**: Total time in bed in minutes.

## Weight DataFrame

- **Id**: Unique identifier for the user.
- **Date**: Date and time when the weight data was recorded (MM/DD/YYYY HH:MM AM/PM).
- **WeightKg**: Weight in kilograms.
- **WeightPounds**: Weight in pounds.
- **Fat**: Body fat percentage.
- **BMI**: Body Mass Index.
- **IsManualReport**: Indicates if the report was manually entered (True) or automatically recorded (False).
- **LogId**: Unique identifier for the weight log entry.
