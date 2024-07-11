# Automated-Weather-Report-Logging-and-Scheduling

This project automates the process of fetching weather data from a weather API, logging weather reports, and scheduling cron jobs for periodic updates. The project consists of a Bash script for retrieving and processing the weather data, along with log files and data storage.

Files

weather.sh: 
The main Bash script to fetch and process weather data.

weather_report.log: 
Log file for weather reports.

temperatures.txt: 
File storing temperature data.

raw_data:
Directory for storing raw API responses.

Bash Scripts

weather.sh
This script performs the following tasks:

Fetches weather data from a specified API.

Logs the weather report to weather_report.log.

Stores the temperature data in temperatures.txt.

Saves the raw API response in the raw_data directory

Cron Jobs

To schedule the weather script to run periodically
