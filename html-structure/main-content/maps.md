# Maps

There are three divergent maps used included in this template.

**1\) Google Maps :**

We can find different styles of this kind in the page [Google Maps](http://coreplus.lorvent.in/google_maps.html).

![](../../.gitbook/assets/clear15.png)

It has the following structure:

```text
<div id="gmap-top" class="map">
</div>
```

_**parameters:**_

i**\) zoom** - This attribute sets the scale of the map \(by default - '8'\).This option is available is in the js file.

```text
zoom : 8
```

ii**\)** **center \[lat , lng\]** - these attributes set the coordinates of the center of the map and the point of the map \(by default - '17.400408 and '78.507905'\). This option is available in Js file.

```text
center : [17.400408, 78.507905]
```

iii**\) hue** - sets the hue of the feature to match the hue of the color supplied. Note that the saturation and lightness of the feature is conserved, which means that the feature will not match the color supplied exactly. Valid values: An RGB hex string, i.e. '\#ff0000'. This opion is available in the js file.

```text
hue : '#0075c2'
```

iv**\) Address** - This feature allows us to mention the current location. This option is available in the js file.

```text
address : "nallakunta,hyderabad"
```

v**\) Marker** - This feature allows the user to explicitly indicate the location. This option is available in the js file.

```text
icon : "images/location-mark.png"
```

**2\) Vector Maps :**

We can find different styles of this kind in the page [Vector Maps](http://coreplus.lorvent.in/vector_maps.html).

![](../../.gitbook/assets/clear16.png)

It has the following Structure

```text
<div id="vmapworld" class="map_size">
    <svg>...</svg>
    ....
    ....
</div>
```

**3\) Advanced Maps :**

![](../../.gitbook/assets/clear17.png)

It has the following Structure

```text
<div id="advanced_map" class="gmap leaflet-container leaflet-fade-anim leaflet-grab leaflet-touch-drag">
   ...
</div>
```

