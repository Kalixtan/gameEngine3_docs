ColourManager Module
====================

This module is used for managing and manipulating colors loaded from "colors.dat".

Functions
---------


.. function:: ColourManager.load(filename)

   Loads the file with the given filename.

   :param str filename: The name of the file.
   
.. function:: ColourManager.getColour(name)

   Returns the color object associated with the given name.

   :param str name: The name of the color.

.. function:: ColourManager.setColour(name, color)

   Sets the color object for the given name.

   :param str name: The name of the color.
   :param color: The color object to set.
   
.. function:: ColourManager.makeInterpolatedColour(factor, baseColour, targetColour)
    Creates a new colour by interpolating between the base colour and the target colour using the specified factor.

    :param float factor: The interpolation factor between 0 and 1.
    :param str baseColour: The base colour to interpolate from.
    :param str targetColour: The target colour to interpolate to.

    :return: The interpolated colour.
