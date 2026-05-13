# Climate Analysis Part 2: Climate Analysis with ClimateStudio

## Importing Model into ClimateStudio
1. Download this small house model here: <a href="https://github.com/amber289/climatestudiotutorial/blob/main/workshops/downloads/singlefamilyhouse.3dm" target="_blank">here</a>

2. This is a representation of single-family residential house. Open this in Rhino7. Make sure z axis is up.
```{image} ../static/clima2/clima2_1.png
:width: 90%
:align: center
```
<br/><br/>

3. The sidebar on the left are your workflow tabs. The baseline tab to be in when creating a model is your layers tab. This helps organize and group created similar polysurfaces and geometries into respective layers. You can also turn on and off the layers to better access visuals of the internal geometry.
```{image} ../static/clima2/clima2_2.png
:width: 90%
:align: center
```
<br/><br/>

4. To conduct climate analysis for your model, navigate to the CS Workflows tab. The dropdown menu displays the different simulations ClimateStudio can do. The first analysis in this tutorial is site analysis. This gives you an overview of the environmental conditions of your site in context with its local weather.
```{image} ../static/clima2/clima2_3.png
:width: 90%
:align: center
```
<br/><br/>

## Uploading Weather Files to ClimateStudio
5. To evaluate your model with the local site weather, upload the weather file you downloaded in Part 1 by clicking open the folder icons.
```{image} ../static/clima2/clima2_4.png
:width: 90%
:align: center
```
<br/><br/>

Choose the weather file and open it.

```{image} ../static/clima2/clima2_4.1.png
:width: 85%
:align: center
```
<br/><br/>

6. It should update and reflect in where the red box is. Check the "show compass" box to see the north arrow appear on the bottom right corner of your Rhino viewport. It is critical that you ensure the north arrow is aligned as you intended because ClimateStudio automatically sets the sun path north based on your Rhino model. By default, the software assumes your project's North is aligned with the positive y-axis. You can fix the orientation by moving the slider of the North Offset or typing in the offset rotation angle in degrees.

```{image} ../static/clima2/clima2_5.png
:width: 90%
:align: center
```
<br/><br/>








