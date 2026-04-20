# Climate Analysis Part 1: Visualizing Weather Data with CBE Clima Tool

## Obtaining weather file
1. Go to <a href="https://climate.onebuilding.org/" target="_blank">climate.onebuilding.org</a>. Go to North-Central America-Region 4 -> North America USA - United States of America.
```{image} ../static/clima1/clima1_1.png
:width: 75%
:align: center
```
<br/><br/>

2. At the United States page. We will use 'ctrl+f' to search for 'manhattan'. It is the 16/17th search as shown below. Click on the link and download it.
```{image} ../static/clima1/clima1_2.png
:width: 100%
:align: center
```
<br/><br/>

3. Unzip the file. You will see 7 files. We will only be using the data from the .epw file. Here is a brief description of the files.
- .clm: weather file for the simulation software ESP-r 
- .wea: weather file for the daylight simulation software daysim
- .PVSyst: weather file for the daylight simulation software PVsyst
- .ddy: design day file
- .rain: precipation data in m/hr if available
- .stat: energyplus weather statistics
```{image} ../static/clima1/clima1_3.png
:width: 85%
:align: center
```
<br/><br/>

