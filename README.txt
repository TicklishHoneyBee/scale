Scale

Scale is a html/javascript app for reading scale drawings. It is a single
self-contained html page, that runs entirely within the browser and so does
not require a http server for use.

USAGE:
Open scale.html in a web browser.
	A publicly available, and usable page is available via github:
		https://ticklishhoneybee.github.io/scale/scale.html
Load in a scale drawing image.
Set the scale of the image by:
	selecting 2 points of a known dimension (such as edge end of a side
		elevation).
	in the pop up form:
		select whether the dimension is horizontal or vertical.
		enter the dimension, either in metres, or feet and inches.
Select the Scale you wish dimension to be shown as from the drop down menu.
Selecting any 2 points on the image will show the dimensions between those
 points.

A scale calculator is also included, allowing dimensions in metres, or feet
 and inches to be converted to scale dimensions.

HOW IT WORKS:
Scale uses a known dimension to calculate the Pixels Per Scale Metre (ppsm)
 of the image, which then allows for the full-size and scale dimensions of
 any two points selected by the mouse to be calculated.

COPYRIGHT:
Scale is released under the terms of the GNU Affero General Public License
 (AGPL), either version 3 of the License, or (at your option), any later
 version.
Essentially what this means:
 You can do whatever you like with it, with two exceptions:
	You must not change the license.
	You must not claim that you wrote it, or that you own the copyright.
 If you make Scale available for use by others, then you must supply them
 with a full copy of Scale, including any changes made by you, if they ask
 for it.
