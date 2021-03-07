# U.S. Flight Cancellation Analysis

## Tools and Skills Used

### Tools
- Python 3.6.3
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - os
  - glob
  - shutil
- Jupyter Notebook

### Skills
- Big data integration
- Data exploration
- Data wrangling
- Data visualisation
- Communication of findings

## Project Details

### Investigation Overview

Flight cancellations are frustrating. They are an unfortunate risk to all air travel. But can you reduce the risk that your flight will be cancelled by choosing a specific carrier, location or time of travel?

Utilizing graphical techniques, an analysis has been conducted of all commercial 21st Century flights in the U.S. using the The Bureau of Transportation Statistics records from 2001 to 2007. The analysis focussed on flight cancellations to elucidate potential answers to the above question, help inform the traveller prior to making their booking and perhaps encourage airlines and/or airports to improve their performance.

### Dataset Overview

The dataset consists of flight arrival and departure details for all commercial flights within the USA, from 2001 to 2007. This is a large dataset with nearly 47 million records in total and takes up almost 6 gigabytes of hard disk space.

The original dataset has 29 columns. However, for the purpose of this analysis, to understand causes of flight cancellations, the dataset has been trimmed to only hold the year, month, day of week and scheduled departure time of flight, the airline, the departure airport, whether the flight was cancelled and the reason for cancellation including carrier, weather, National Aviation System or security.

### Summary of Findings

Most flights that were delayed only had a few minutes delay. Late Aircraft Delay had the greatest sum of delays in minutes with Security delays having the least. Security delays caused flight delays of less than 500 minutes, whereas carrier delays resulted in the lengthiest delays in the dataset.

The number of flights and flight cancellations in the U.S. between 2001 and 2007 increased. Crucially, so had the percentage of flights cancelled suggesting the industry was not improving in this factor. 2001 had the greatest number of cancelled flights, likely due to the 9/11 terror attack.

Flight cancellations were more likely during Winter months, during the working week and in the early morning or late afternoon.

Major international airports had a higher proportion of flight cancellations with LaGuardia, Chicago O'Hare and Newark being the worse performing.

American Eagle Airlines had the most flight cancellations between 2001 and 2007. The most common reason for most airlines for cancellation was themselves, followed by weather and the National Aviation System. Security very rarely was a cause for cancellation. All U.S. airlines had increased their percentage of flights cancelled between 2003 and 2007 with United Air Lines, Atlantic Southeast Airlines and JetBlue Airways having the greatest increases. 

### Key Insights for Presentation

The final presentation of the results can be found [here](Presentation_Explanatory_US_Flight_Cancellation.ipynb). 

Flight cancellations were focussed on for the presentation. Specifically, attempting to identify whether the industry had decreased the number of flight cancellations between 2001 and 2007, what airports were most likely to suffer flight cancelations, when and which airlines were most likely to suffer flight cancelations.

