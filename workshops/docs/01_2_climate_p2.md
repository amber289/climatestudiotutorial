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

4. To conduct climate analysis for your model, navigate to the CS Workflows tab. The dropdown menu displays the different simulations ClimateStudio can do. The first analysis in this tutorial is location analysis. This gives you an overview of the environmental conditions of your site in context with its local weather.
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

Note the summarized information that the location subpanel gives you about the weather such as the climate zone and heating & cooling load conditions.

```{image} ../static/clima2/clima2_5.png
:width: 90%
:align: center
```
<br/><br/>

## Visualizing Sun Path
7. In the site analysis subpanel, navigate to the sunpath tab. Check the box for "3d Sun Path" and then click "set position" to set where the reference point of the sun path is.
```{image} ../static/clima2/clima2_6.1.png
:width: 90%
:align: center
```
<br/><br/>

8. Set the point cursor to the midpoint of the cross construction line and click. You will see the center of the 3D sun path be relocated to that point.
```{image} ../static/clima2/clima2_6.2.png
:width: 90%
:align: center
```
<br/><br/>

9. Check the Shadows box to enter a display mode that casts direct shadows from the sun's position.
```{image} ../static/clima2/clima2_7.4.png
:width: 90%
:align: center
```
<br/><br/>

10. Use the date and time dropdown settings to control the sun's arc and position along the path. We mostly only care about the summer (June 21) and winter (Dec 21) solstices because those provide information about the extreme scenarios. To evaluate on a specific day or time, move the slider position using left or right arrow keys. Try comparing the sun path on the two solstices.
    
```{image} ../static/clima2/clima2_7.7.png
:width: 90%
:align: center
```
<br/><br/>

11. You will notice that during the summer solstice scenario, the sun travels along the longest arc of the sun path and reaches it highest altitude. The building will recieve the maximum daylight, but will be at the highest risk of overheating and glare, especially on the south side. In the winter solstice, the sun is at its shortest arc and lowest, offering the least natural light and solar heat. This demands the most out of passive solar heating, which is a building technique that uses a building's architecture and material to provide warmth without the need of mechanical devices.

```{image} ../static/clima2/clima2_7.5.png
:width: 90%
:align: center
```
<br/><br/>

```{image} ../static/clima2/clima2_8.png
:width: 90%
:align: center
```
<br/><br/>

Summer Solstice Sun Path (GIF)
![Summer Solstice](../static/clima2/clima2_7.3.gif)

<br/><br/>

Winter Solstice Sun Path (GIF)
![Winter Solstice](../static/clima2/clima2_9.gif)

## Wind Rose
12. In the site analysis subpanel, navigate to the wind rose tab. Check the box for "Show 3D Wind Rose" and then similar to the sun path, click "Set Position" to set the reference point of where the wind rose originates. 
```{image} ../static/clima2/clima2_10.2.png
:width: 90%
:align: center
```
<br/><br/>

13. You will see a polar graph imposed over your house model.
```{image} ../static/clima2/clima2_11.2.png
:width: 90%
:align: center
```
<br/><br/>





