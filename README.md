3D_Animation
============
3D Animation is a plugin for Fiji/ImageJ for creating 3D and 4D animations of microscope data. In contrast to existing 3D 
visualization packages, animations are not keyframe-based, but are described by a natural language-based syntax.

Find more information at https://bene51.github.io/3D_Animation

Requirements:
-------------
* 64-bit Operating System (Linux, Mac OS X or Windows)
* Up-to-date Fiji installation (http://www.fiji.sc)
* OpenCL 1.2-capable Graphics Card or better

Installation:
-------------
* Start Fiji
* Click on Help>Update...
* Click on Manage update sites
* Check the 3D Animation site
* Click on Close
* Click on Apply changes
* Restart Fiji
* Installation typically takes not longer than a couple of minutes

Demo:
-----
* Start Fiji
* Click on File>Open Samples>T1 Head
* Click on Plugins>3D Animation>3D Animation
* In the "Interactive Raycaster" window, click on "show" next to "Animation"
* Click on "Start text-based animation editor"
* In the editor window, type the following text:
  From frame 0 to frame 200 rotate by 360 degrees horizontally
* Click on "Run"
  This will render 200 frames of a movie sequence, within which the MRI data set rotates by 360 degrees.

Rendering of 200 frames of this data set will typically take less than a minute on an OpenCL-enabled Graphics Card.
The resulting stack can be saved as a video file using Fiji's File>Save As>AVI... command.

To run the software on another data set, open a different image stack (instead of the T1 Head sample data).

More information is available at https://bene51.github.io/3D_Animation

