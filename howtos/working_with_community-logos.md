# Introduction
The Eiffel Community logos are created using [Gimp](https://www.gimp.org/). They all exist in one Gimp [xcf file](../resources/eiffel-community-logos.xcf), with multiple layers in it. To create a new variant of the logo for a new community tool, you need to add new layers in that image to reflect that.

# Exporting to PNG
In each community repo there should be an *images* folder containing the logo for that specific community tool. To create such a PNG file you should open the xcf file in Gimp, select the layers you wish to be visible in your exported logo image file and then select File->Export As... to export it.

# Exporting to SVG
The xcf file is a bitmap image file and SVG is a vector image format, so there is no obvious way to convert to SVF. But it can be done quite easily in a two-step process. First, make sure you have a PNG version of the logo you wish to convert to SVG (following the *Exporting to PNG* instruction above). Then import that PNG image into [Inkscape](https://inkscape.org/) chosing the 'Embed' option in Inkscapes import dialog. In Inkscape do this:
- Select the logo
- Choose 'Path' -> 'Trace Bitmap...' (or Shift-Alt-B)
- Choose 'Colors' and set number of Scans to e.g. 32 (to get some decent graytones in the half-circle). The higher number of Scans the bigger the image file will be.
- Check with 'Preview' or 'Update', and Click OK when done. Now you have added a vector image to your Inkscape canvas.
- Remove the old bitmap picture (it is behind the newly created vector image in the canvas)
- Resize the vector image if needed so that it fits in your canvas in Inkscape (hold Ctrl to keep aspect ratio)
- Save as an SVG file
- Done!
