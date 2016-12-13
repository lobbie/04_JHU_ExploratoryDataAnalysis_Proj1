# Coursera Johns Hopskins University Data Science Course 04 Exploratory Data Analysis Project 1
## Author:  William Thong

The purpose of this project is to demonstrate the ability to use R Base Plotting System to plot and output graphs using the “Individual household electric power consumption Data Set” from UC Irvine Machine Learning Repository.  The overall goal here is simply to examine how household energy usage varies over a 2-day period in February, 2007.  The task is to reconstruct the following 4 plots, all of which were constructed using the base plotting system.    

# Submissions
You will be required to submit:    

1. 4 'png' image files containing the plots each and,    
2. 4 R code files which contain the code that was used to generate each of the 4 plots.    

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

# Instructions for reproducing this R project

1. Clone/download this repo to your local directory.  
2. Navigate to the directory where you saved the repo and ensure that the source data files are in the **"./SourceData/UCI HAR Dataset"** folder of your directory. If you do not have a copy of the source data files, the R script will download a copy for you during runtime and through your internet connection.   
3. Locate and open the R script **run_analysis.R** with your favorite R client (RStudio recommended). Modify the directory path in ```setwd()``` to set the working directory to your directory.  
4. Run the R script **run_analysis.R**.  
5. The R script will generate **run_analysis.html** and **codebook.html**.  Open them with your favorite browser to view the generated results.  

If you are using RStudio, you can view and run the R Notebooks interactively.  Assuming you were using RStudio to set working directory and had ran **run_analysis.R** previously, and within the same R session,

- Open **run_analysis.Rmd** and **codebook.Rmd**.
- You can run these R Notebooks interactively by running individual or all code chunks.

# Output produced
The following are the output,

* Tidy datasets in tab-delimited text format:  **TidyData.txt** and **TidyDataAvg.txt**.  
* Results in HTML format:  **run_analysis.html** and **codebook.html**.
* Results in Notebook HTML format:  **run_analysis.nb.html** and **codebook.nb.html**





