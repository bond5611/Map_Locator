<h1>Map Locator:</h1><br>
<p>Map locator is easy to use plugin, which uses map API of google, to show users any location in your website page or widget. The most common use of this plugin would be to show website visitors where in map your company, hotel, hospital, school, college, university locate. All you need to know are coordinates of your position, you fill them out and there you are with google map locating your position.</p>
<h2>How to Use?</h2>
<p>Map locator comes with two in one, “widget and short code”, uses.</p>
<h3>Map Locator Widget:</h3>
<p>To display map in your sidebar you need to activate the plugin. After activating the plugin you will be able to see our plugin by the name “Map Locator” in wordpress widget section. You will have to drag that to sidebar to active. By default if you don’t fill in the form the plugin will display our location (Don’t worry you can easily change them, see modify plugin section in this document). The widget form has four fields namely, title, latitude, longitude, and zoom. Zoom tell the zoom of google map you want to display and it ranges from value 1 to 20. The latitude value can lie between -90 to +90 and longitude value can lie between -180 to +180. In case if you don’t give it right values we will still show our location on your map as default.</p>
<h3>Map Locator short code:</h3>
<p>You can use short code in your pages and posts, all you will need to write.</p>
1.	[Map_Locator]
<p>Since this doesn’t tell proper coordinates the map will show the default location which is ours.
[Map_Locator] takes five difference values.</p>
<ul>
<li>Zoom: Tells zoom of google map. (Default is 14)</li>
<li>Width: Tells width of google map which will appear on your website. (Default is 725)</li>
<li>Height: Tells height of google map which will appear on your website. (Default is 350)</li>
<li>Latitude: Tells latitude position of your location in google map. (Default is 24.878489)</li>
<li>Longitude: Tells Longitude position of your location in google map. (Default is 67.064235)</li>
</ul>
<h4>Example:</h4>
[Map_Locator width=”850” height=”470” zoom=”14” latitude=”24.678” longitude=”67.852”]
<h2>Changing Default Value:</h2>
<p>If you exact our plugin to some folder and open up our file that is map_locator.php, replace all occurrences of 24.878489 with your latitude value and 67.064235 with your longitude value.</p>
<h3>Better Use Now:</h3>
<p>You can now just drag and drop the widget without entering any value to the form, and still you will see your location in map, it is because you have replaced the default coordinates. If you fill form your default values will override by new ones.</p>
<p>Similarly writing short code [Map_Locator] will display your location. Guess what? You still have access to those features to override default with new values at any time.</p>
<p>In most cases the plugin not only shows the desired location but also the nearest location listed in google maps. Hence makes your appearance and business grow more quickly.</p>
<p>Hope you understand the documentation; feel free to drop any comments and feedbacks about this plugin.</p>

