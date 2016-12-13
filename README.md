# Coursera Johns Hopskins University Data Science Course 04 Exploratory Data Analysis Project 1
## Author:  William Thong

The purpose of this project is to demonstrate the ability to use R Base Plotting System to plot and output graphs using the “Individual household electric power consumption Data Set” from UC Irvine Machine Learning Repository.  The overall goal here is simply to examine how household energy usage varies over a 2-day period in February, 2007.  The task is to reconstruct the 4 required plots, all of which were constructed using the base plotting system.    

# Submissions
You will be required to submit:    

1. 4 individual 'png' image files containing the plots and,    
2. 4 individual R code files which contain the code that was used to generate each of the 4 plots.    

# Source Data Details    

* Data Prodvider: [UC Irvine Machine Learning Repository](http://archive.ics.uci.edu/ml/)
* Dataset: [Electric power consumption 20Mb](https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip)
* Description: Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.     

The following descriptions of the 9 variables in the dataset are taken from the UCI web site:     

* Date: Date in format dd/mm/yyyy     
* Time: time in format hh:mm:ss
* Global_active_power: household global minute-averaged active power (in kilowatt)
* Global_reactive_power: household global minute-averaged reactive power (in kilowatt)
* Voltage: minute-averaged voltage (in volt)
* Global_intensity: household global minute-averaged current intensity (in ampere)
* Sub_metering_1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).
* Sub_metering_2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.
* Sub_metering_3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.

# Instructions for reproduction

1. Clone/download this repo to your local directory.  
2. Navigate to the directory where you saved the repo and ensure that the source data file **household_power_consumption.txt** is in said directory.
3. In the directory, you will find 4 R scripts namely, **plot1.R; plot2.R; plot3.R and plot4.R.**.  Each of these 4 R scripts will import the raw data file, generate the required plot and output the required image file in png format.
4. Before you run **each R script**, please ensure you have,  
  * The R packages 'dplyr' and 'sqldf' installed and updated.
  * Set the working directory to your working directory using the ```setwd``` function within the code.     

# Output produced
After successful run of each R script, you will find 4 png files in your working directory namely, **plot1.png; plot2.png; plot3.png and  plot4.png.**





