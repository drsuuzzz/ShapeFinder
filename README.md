ShapeFinder
===========

<h1>What is ShapeFinder?</h1>
It's a tool for processing trace data for analysis of SHAPE data.  It was written primarily by Morgan Giddings and Jessica Severin at the University of Wisconsin-Madison, in Lloyd Smith's lab and was known as BaseFinder at that time.  The program was started in 1991 by Morgan, and continued refinement through 1997.  

<h1>How to Install?</h1>
Prior to installation, it is best to manually delete the previously installed BaseFinder and/or ShapeFinder.  Next, Drag and Drop the ShapeFinder.app file into the Applications folder.  

<h1>How to Build?</h1>
You'll need to download the source code from the BaseFinder repository.  Open the file BaseFinder/BaseFinder.xcodeproj in Xcode.  Select the ShapeFinder Target and build.  The BaseFinder project is set up to build as a universal binary and supports Mac OS X 10.4 and 10.5. Have fun! 


<h1>Other contributors:</h1>
Mike Koehrsen<br>
Suzy (Vasa) Stiegelmeyer<br>
Nicolas Guex<br>


<h1>ShapeFinder Release Notes</h1>
<h2>Version 0.2</h2>
-GUI issue with Leopard (10.5) items in lists, such as Script Inspector, etc. were not highlighting when selected.<br>
-Removed Deconvolution Tool and Filter FFT tools from the list of tools<br>
-Added Mobility Cubic tool to the list of tools<br>

<h2>Version 0.1</h2>
-Birth of ShapeFinder name.  Based on BaseFinder version 6.2.10

<h2>Known bugs/issues</h2>
- BaseFinder cannot save in ESD format.  So, the first time the user tries to save an ESD file after opening, the save panel will come up, requiring the choice of a new format.
 
