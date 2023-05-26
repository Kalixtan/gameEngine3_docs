DrawList Module
================

This section provides documentation for functions inide the "drawList" object.

.. function:: drawList.setupWorldView()

   Sets up the world view for the draw list.

.. function:: drawList.reset()

   Resets the draw list, clearing any previously set attributes and matrices.

.. function:: drawList.pushAttributes()

   Pushes the current attribute state onto the attribute stack.

.. function:: drawList.popAttributes()

   Pops the attribute state from the top of the attribute stack.

.. function:: drawList.setAttrDepthTest(enabled)

   Sets whether depth testing should be enabled or disabled.

   :param bool enabled: Specifies whether depth testing should be enabled (``true``) or disabled (``false``).

.. function:: drawList.pushMatrix()

   Pushes the current matrix state onto the matrix stack.

.. function:: drawList.popMatrix()

   Pops the matrix state from the top of the matrix stack.

.. function:: drawList.setColour(r, g, b)

   Sets the color for subsequent draw operations.

   :param float r: The red component of the color (0.0 - 1.0).
   :param float g: The green component of the color (0.0 - 1.0).
   :param float b: The blue component of the color (0.0 - 1.0).

.. function:: drawList.drawTextureByHandle(x1, y1, x2, y2, x3, y3, x4, y4, handle)

   Draws a texture using the specified handle and vertex coordinates.

   :param float x1: The x-coordinate of the first vertex.
   :param float y1: The y-coordinate of the first vertex.
   :param float x2: The x-coordinate of the second vertex.
   :param float y2: The y-coordinate of the second vertex.
   :param float x3: The x-coordinate of the third vertex.
   :param float y3: The y-coordinate of the third vertex.
   :param float x4: The x-coordinate of the fourth vertex.
   :param float y4: The y-coordinate of the fourth vertex.
   :param int handle: The handle of the texture to draw.
