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

## Load weather file in CBE Clima Tool
1. Now we will go to the <a href="https://clima.cbe.berkeley.edu/" target="_blank">CBE Clima Tool</a>. At the page, click on 'Drag and Drop or Select an EPW file from your computer' and select the New York Manhattan file .epw file we downloaded.
```{image} ../static/clima1/clima1_4.png
:width: 85%
:align: center
```
<br/><br/>

2. It will load the weather file as shown below.
```{image} ../static/clima1/clima1_5.png
:width: 75%
:align: center
```
<br/><br/>

3. Go to the 'Climate Summary' tab. We can see a brief summary of the climate. Previous versions of the CBE Clima Tool also indicated the Köppen-Geiger climate classification. The <a href="https://en.wikipedia.org/wiki/K%C3%B6ppen_climate_classification#Overview" target="_blank">Köppen-Geiger climate classification</a> is a system that categorizes climates into 5 main groups based on temperature and precipitation patterns. New York is classified as Cfa, where C(Temperate), f(No dry season) and a(hot summer), which means it is a humid subtropical climate. 
```{image} ../static/clima1/clima1_6.png
:width: 85%
:align: center
```
<br/><br/>



