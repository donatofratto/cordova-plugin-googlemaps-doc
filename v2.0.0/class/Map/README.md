# The methods of Map class

## Methods

<table >
    <tr>
        <th><a href="./getMap/README.md">getMap()</a></th>
        <td>Gets a new map class instance.</td>
    </tr>
    <tr>
        <th><a href="./setDiv/README.md">setDiv()</a></th>
        <td>Changes the map div.</td>
    </tr>
    <tr>
        <th><a href="./setMapTypeId/README.md">setMapTypeId()</a></th>
        <td>Changes the map type id.</td>
    </tr>
    <tr>
        <th><a href="./animateCamera/README.md">animateCamera()</a></th>
        <td>Moves the camera <b>with animation</b>.</td>
    </tr>
    <tr>
        <th><a href="./moveCamera/README.md">moveCamera()</a></th>
        <td>Moves the camera <b>without animation</b>.</td>
    </tr>
    <tr>
        <th><a href="./getCameraPosition/README.md">getCameraPosition()</a></th>
        <td>Get the current camera position, including the target, zoom, tilt and bearing.</td>
    </tr>
    <tr>
        <th><a href="./getCameraTarget/README.md">getCameraTarget()</a></th>
        <td>Get the current camera target position.</td>
    </tr>
    <tr>
        <th><a href="./getCameraZoom/README.md">getCameraZoom()</a></th>
        <td>Get the current camera zoom level.</td>
    </tr>
    <tr>
        <th><a href="./getCameraBearing/README.md">getCameraBearing()</a></th>
        <td>Get the current camera bearing.</td>
    </tr>
    <tr>
        <th><a href="./getCameraTilt/README.md">getCameraTilt()</a></th>
        <td>Get the current camera tilt (view angle).</td>
    </tr>
    <tr>
        <th><a href="./setCameraTarget/README.md">setCameraTarget()</a></th>
        <td>Set the center position of the camera view.</td>
    </tr>
    <tr>
        <th><a href="./setCameraZoom/README.md">setCameraZoom()</a></th>
        <td>Set zoom level of the camera.</td>
    </tr>
    <tr>
        <th><a href="./setCameraTilt/README.md">setCameraTilt()</a></th>
        <td>Set the camera view angle.</td>
    </tr>
    <tr>
        <th><a href="./setCameraBearing/README.md">setCameraBearing()</a></th>
        <td>Set the camera bearing.</td>
    </tr>
    <tr>
        <th><a href="./panBy/README.md">panBy()</a></th>
        <td>Change the center of the map by the given distance in pixels.</td>
    </tr>
    <tr>
        <th><a href="./getVisibleRegion/README.md">getVisibleRegion()</a></th>
        <td>Get the current visible region (sw and ne).</td>
    </tr>
    <tr>
        <th><a href="./getMyLocation/README.md">getMyLocation()</a></th>
        <td>Get the current device location.</td>
    </tr>
    <tr>
        <th><a href="./setClickable/README.md">setClickable()</a></th>
        <td>Set false to ignore all clicks on the map.</td>
    </tr>
    <tr>
        <th><a href="./remove/README.md">remove()</a></th>
        <td>Destroy a map completely.</td>
    </tr>
    <tr>
        <th><a href="./clear/README.md">clear()</a></th>
        <td>Remove all overlays, such as marker.</td>
    </tr>
    <tr>
        <th><a href="./fromLatLngToPoint/README.md">fromLatLngToPoint()</a></th>
        <td>Convert the unit from LatLng to the pixels from the left/top of the map div.</td>
    </tr>
    <tr>
        <th><a href="./fromPointToLatLng/README.md">fromPointToLatLng()</a></th>
        <td>Convert the unit from the pixels from the left/top to the LatLng.</td>
    </tr>
    <tr>
        <th><a href="./setMyLocationEnabled/README.md">setMyLocationEnabled()</a></th>
        <td>Set true if you want to show the MyLocation button.</td>
    </tr>
    <tr>
        <th><a href="./getFocusedBuilding/README.md">getFocusedBuilding()</a></th>
        <td>Get the currently focused building.</td>
    </tr>
    <tr>
        <th><a href="./setIndoorEnabled/README.md">setIndoorEnabled()</a></th>
        <td>Set true if you want to show the indoor map.</td>
    </tr>
    <tr>
        <th><a href="./setTrafficEnabled/README.md">setTrafficEnabled()</a></th>
        <td>Set true if you want to show the traffic layer.</td>
    </tr>
    <tr>
        <th><a href="./setCompassEnabled/README.md">setCompassEnabled()</a></th>
        <td>Set true if you want to show the compass button.</td>
    </tr>
    <tr>
        <th><a href="./setAllGesturesEnabled/README.md">setAllGesturesEnabled()</a></th>
        <td>Sets the preference for whether all gestures should be enabled or disabled.</td>
    </tr>
    <tr>
        <th><a href="./setVisible/README.md">setVisible()</a></th>
        <td>Set visiblity of the map.</td>
    </tr>
    <tr>
        <th><a href="./setPadding/README.md">setPadding()</a></th>
        <td>Adjust the map padding.</td>
    </tr>
    <tr>
        <th><a href="./setOptions/README.md">setOptions()</a></th>
        <td>Adjust the map padding.</td>
    </tr>
    <tr>
        <th><a href="./toDataURL/README.md">toDataURL()</a></th>
        <td>Generate the map screen capture image as base64 encoded data, like HTML5's Canvas.</td>
    </tr>
    <tr>
        <th><a href="../Marker/addMarker/README.md">map.addMarker()</a></th>
        <td>Add a <a href="../Marker/index/README.md">marker</a>.</td>
    </tr>
    <tr>
        <th><a href="../Polyline/addPolyline/README.md">map.addPolyline()</a></th>
        <td>Add a <a href="../Polyline/index/README.md">polyline</a>.</td>
    </tr>
    <tr>
        <th><a href="../Polygon/addPolygon/README.md">map.addPolygon()</a></th>
        <td>Add a <a href="../Polygon/index/README.md">polygon</a>.</td>
    </tr>
    <tr>
        <th><a href="../Circle/addCircle/README.md">map.addCircle()</a></th>
        <td>Add a <a href="../Circle/index/README.md">circle</a>.</td>
    </tr>
    <tr>
        <th><a href="../GroundOverlay/addGroundOverlay/README.md">map.addGroundOverlay()</a></th>
        <td>Add a <a href="../GroundOverlay/index/README.md">ground overlay</a>.</td>
    </tr>
    <tr>
        <th><a href="../TileLayer/addTileLayer/README.md">map.addTileLayer()</a></th>
        <td>Add <a href="../addTileLayer/index/README.md">tile layer</a>.</td>
    </tr>
    <tr>
        <th>map.addKmlOverlay()</th>
        <td><span class="highlight">Not ready yet currently</span></td>
    </tr>
</table>
