# Introductory Guide to Kepler.gl
_Prepared by Alyssa Lopez_

This resource was adapted for LEADR classes from [this](http://drstephenrobertson.com/blog-post/teaching-digital-mapping-with-kepler-gl/) tutorial.


## Basic Information
Kepler.gl is a platform designed for geospatial data analysis, making it possible to investigate trends on various geographical levels, including region, state, city, and county. A variety maps, such as points, networks, and chloropeths, can be created (or compared) with filters and layering,

For Kepler to be able to make a map from data, there needs to be latitudinal and longitudinal information within your dataset. In some cases, a dataset may have latitude and longitude in one single column, separated by a comma. Kepler **will not** be able to read these values. For more information on the types of files and formats that Kepler accepts, refer to "Add Data on the Map" on the [user guide](https://github.com/uber/kepler.gl/blob/master/docs/j-get-started.md)

**Potential Data Sets**
* [Alabama Slave Interviews](http://drstephenrobertson.com/blog-post/teaching-digital-mapping-with-kepler-gl/) created by Dr. Robertson    
* [Alabama County Unemployment data](https://github.com/leadr-msu/kepler-gl/blob/master/AL-countyunemployment.geojson)


## Getting Started
1. Head to [kepler.gl](kepler.gl) and select "Get Started." Next, you'll need to upload your dataset.
2. You should now see a dark map with light points throughout (which represent your location data). If you roll over a point with your mouse, a pop-up will appear with the information from your dataset. You can change this later.
3. If you click on a point, it will remain fixed and a green pin will appear. To unpin it, click that green pin.
**N.B.:** Multiple rows of data with the same latitude & longitude coordinates will not be made separate by Kepler and the points will show up on top of each other with only the top one displaying.


## Base Map
Before moving forward and manipulating and analyzing your map, you can adjust some basic visual settings. To do so, click on that looks like sliders on the upper-left hand side of your screen.
*  Map Style:
    1. There are four options for your larger map color: Dark, Light, Muted Light, and Muted Night.
    2. I find that the light options are less accessible than the darker options when some layers are toggled on.
* Map Layers:
    1. There are six options for your basic map layers that can be turned on/off by clicking on the eye icon to the left of them. You also have the option of moving certain layers to the top of the pile, allowing them to appear over things such as points and other layers.
    2. Label: When this is on, your map will have various city and state labels on view, depending on the zoom level.
    3. Road: When this is on, roads are visible.
    4. Border: When this is on, border lines are a visible. In our case, state lines are the dotted lines that appear.
    5. Building:
    6. Water: When this is on, all waterways on your map are visible
    7. Land:
