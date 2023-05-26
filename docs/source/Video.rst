Video
================

This module provides functions for working with video-related operations.

Functions
---------

.. function:: Video.getTexture(filename, area)

   Loads a texture from the specified file and returns its handle.

   :param str filename: The filename of the texture.
   :param str area: The area where the texture file is located.

.. function:: Video.unloadTextureByHandle(handle)

   Unloads the texture specified by its handle.

   :param int handle: The handle of the texture to unload.

.. function:: Video.refreshAllGraphicColours()

   Refreshes all graphic colors.

.. function:: Video.pushAttributes()

   Saves the current video attributes.

.. function:: Video.popAttributes()

   Restores the previously saved video attributes.

.. function:: Video.setAttrDepthTest(enabled)

   Enables or disables depth testing.

   :param bool enabled: True to enable depth testing, False to disable.

.. function:: Video.setupAspectRatioOrthoView()

   Sets up an orthographic view with the current aspect ratio.

.. function:: Video.getAspectRatio()

   Returns the current aspect ratio.

.. function:: Video.setColour(r, g, b, a)

   Sets the current color to the specified RGBA values.

   :param float r: The red component (0-1).
   :param float g: The green component (0-1).
   :param float b: The blue component (0-1).
   :param float a: The alpha component (0-1).

.. function:: Video.beginShape(shapeType)

   Begins drawing a shape of the specified type.

   :param int shapeType: The type of shape.

.. function:: Video.plotVertex(x, y)

   Adds a vertex to the currently active shape.

   :param float x: The x-coordinate of the vertex.
   :param float y: The y-coordinate of the vertex.

.. function:: Video.endShape()

   Finishes drawing the current shape.

.. function:: Video.translate(x, y)

   Translates the coordinate system by the specified amount.

   :param float x: The amount to translate along the x-axis.
   :param float y: The amount to translate along the y-axis.

.. function:: Video.printUntranslated(x, y, text, size, align)

   Prints the specified text at the given position with the specified size and alignment.

   :param float x: The x-coordinate of the position.
   :param float y: The y-coordinate of the position.
   :param str text: The text to print.
   :param float size: The size of the text. (Height in pixels?)
   :param int align: The alignment of the text.

.. function:: Video.print(x1, y1, x2, y2, text, size, align)

   Prints the specified text at the given position with the specified size and alignment.

   :param float x1: The top left x-coordinate of the text box.
   :param float y1: The top left y-coordinate of the text box.
   :param float x2: The bottom right x-coordinate of the text box.
   :param float y2: The bottom right y-coordinate of the text box.
   :param str text: The text to print.
   :param float size: The size of the text. (Height in pixels?)
   :param int align: The alignment of the text.

.. function:: Video.loadTexture(filename, area)

   Loads a texture from the specified file and area.

   :param str filename: The filename of the texture.
   :param str area: The area where the texture file is located.

.. function:: Video.restartVideo(width, height, fullScreen, unk)

   Restarts the video system with the specified parameters.

   :param int width: The width of the video.
   :param int height: The height of the video.
   :param bool fullScreen: True for full-screen mode, False for windowed mode.
   :param int ink: UNKNOWN.

