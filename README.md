# Charmix
A frame & sequence composition tool for point & click pixel-style character art. To run this you need Octave, which is available for many platforms: https://www.gnu.org/software/octave/index , and run the *.m script with it.

![Screenshot of Charmix](https://github.com/coscholz1984/Charmix/blob/main/Screenshot_v2.jpg?raw=true)
![Screenshot of Charmix](https://github.com/coscholz1984/Charmix/blob/main/Screenshot_v3.jpg?raw=true)\

The script has been written and tested in Octave 6.2.0.

A sample for character art with corresponding segmentation maps is provided based on the default template of Adventure Game Studio: https://www.adventuregamestudio.co.uk/ and https://github.com/adventuregamestudio/ags authored by Chris Jones (see [License](https://www.adventuregamestudio.co.uk/site/ags/legal/)) and many others (see [Artistic License 2.0](https://github.com/adventuregamestudio/ags/blob/master/License.txt) and [Credits](https://github.com/adventuregamestudio/ags/blob/master/Copyright.txt)).  
The source to this template is https://github.com/caesarcub/AGS-SCI-Template - by ProgZmax, CaesarCub, Hobo, Selmiak, Jim Reed published under the [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.  

The tools is based on segmentation maps for individual parts of the image: Hair, skin, eyes, torso, belt, arms, pants, shoes. Individual segments are defined by unique colors (red, green, blue, black, cyan, yellow, black, gray). See the code or example images for exact RGB values. Multiple sequences with corresponding segmentations are loaded and can then be combined and composed into a new sequence. The composed sequence can be exported as a series of png files. The sample art inherits the license mentioned above, the source code is distributed as public domain, otherwise known as CC0.
