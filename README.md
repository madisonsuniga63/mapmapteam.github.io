MapMap is an open source video mapping software.

# Download and install
Use the latest version of MapMap you can find at these links:
- [Source code Git repository of MapMap](https://github.com/mapmapteam/mapmap)
- [Download MapMap for macOS](http://download.mapmap.info/osx/)
- [Download MapMap for Windows](http://download.mapmap.info/windows/)
- [Source code tarballs of MapMap](http://download.mapmap.info/tarballs/)
- [Install MapMap on Ubuntu GNU/Linux](https://launchpad.net/~mapmap/+archive/ubuntu/mapmap)

# Documentation
How to use MapMap to create to do video mapping.

## Launching the application
On Apple OS X, open the application by either double-clicking on its icon in the Finder, or by clicking on its icon in the Dock. To display more information about the errors that might occur, launch MapMap from the command line. To do so, open the Terminal application, that is located in /Applications/Utilities, type this: /Applications/mapmap.app/Contents/MacOS/MapMap, and hit the Return key.

On Debian or Ubuntu GNU/Linux, find its icon in the application menu and activate it. You can also run it via the command-line by typing "mapmap".

## Paints and mappings
A paint is some materials to be drawn. Currently supported paint types are color paint and media paint.

A mapping is a shape in the output window on which to display some paint. Currently supported shapes are: quads and circles. When quads have a dimension of two by two (2x2) vertices, they are actuals quads. When they have more than 2x2 vertices, they are called meshes. A mesh is a grid of vertices that allow more flexible mapping.

## The elements of the user interface
The application has a main window and an output window. The main window includes the toolbar, input viewport, the output viewport, the list of paints, the list of mappings and the property inspector.

Make the output window fullscreen before starting to do video mapping on an actual object. This is necessary so that the pixel positions match the actual location of the pixels drawn by the projector. One should also make sure to use the native resolution of the projector, for best results, if any.

Note that there are handles that are drawn on the mappings in the output window, to ease editing. For a show, one will most probably want to disable them. Uncheck the "View > Display canvas controls" menu item to do so.

## Create a media paint
Choose File > Import media source file... or click on the button in the toolbar. Choose a media file using the dialog.

A simple sample clip can be found here: http://download.blender.org/durian/trailer/

## Create a mapping
First, select the desired paint for the mapping in the paint list. To create a quad, click on the "Choose Quad/Mesh" button in the toolbar. Move around the vertices of the quad by click and dragging near them. The closest vertex should be dragged. You can also use the number boxes in the property inspector to move the vertices.

To make a mesh from a quad, change its dimension using its width and height mumber boxes.

Creating a triangle is very similar to creating a quad. Move around its vertices with the mouse.

To create a circle do the same as for a quad or a triangle. Changing its size, orientation and position is a bit tricky, though. Play around by drag and dragging the vertices of the blue shape that is in the input and output viewports.

## Create a color paint
Color paints can be used as black masks and must be created the same way as a media paint, but it's a color dialog instead.

## Destroy a mapping
Mapping can be destroyed simply by selecting it in the mapping list, and then choosing the "Edit > Delete" menu item.

## Destroy a paint
Paints can be destroyed simply by selecting it in the paint list, and then choosing the "Edit > Delete" menu item. Since all the mappings that use that paint will also be delete, a dialog will ask you for confirmation.

## Save the project to a file
To save the current project, choose "File > Save as..." and then choose a file name. The extension file is ".mmp", but the file format is simply XML, a very common one.

## Load a project from a file
To load a project from a file, choose "File > Open...".

# Support or Contact
- [MapMap mailing list](https://listes.koumbit.net/cgi-bin/mailman/listinfo/mapmap-list-mapmap.info)
- The #mapmap IRC channel on Freenode
- Write to us at info at mapmap dot info

# Partners

MapMap is made possible thanks to the generous support of the following organizations:
- [Organisation Internationale de la Francophonie](https://www.francophonie.org)
- [Perte de Signal](http://perte-de-signal.org)
- [Ker Thiossane](http://www.ker-thiossane.org)
- [Conseil des Arts et des Lettres du Québec](https://www.calq.gouv.qc.ca)
- [Millumin](http://www.millumin.com)
