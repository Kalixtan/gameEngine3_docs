

Math Module
-----------

This module provides mathematical functions and constants.

.. function:: MATH_MAX(a, b)

   Returns the maximum value between a and b.

   :param float a: The first value.
   :param float b: The second value.

.. function:: MATH_MIN(a, b)

   Returns the minimum value between a and b.

   :param float a: The first value.
   :param float b: The second value.

.. function:: MATH_REAL(i)

Returns the real component of a complex number. (To verify?)

:param complex i: The complex number.

:return: The real component of the complex number.

.. function:: MATH_COS(i)

Returns the cosine of the specified angle.

:param float i: The angle in radians.

:return: The cosine of the angle.

.. function:: MATH_SIN(i)

Returns the sine of the specified angle.

:param float i: The angle in radians.

:return: The sine of the angle.

.. function:: MATH_COS_POW(i)

Returns the cosine of the specified angle raised to the power of 2.

:param float i: The angle in radians.

:return: The result of cosine squared.

.. function:: MATH_SIN_POW(i)

Returns the sine of the specified angle raised to the power of 2.

:param float i: The angle in radians.

:return: The result of sine squared.

.. function:: MATH_ABS(i)

Returns the absolute value of the specified number.

:param float i: The number.

:return: The absolute value of the number.

.. function:: MATH_INT(i)

Returns the integer part of the specified number.

:param float i: The number.

:return: The integer part of the number.

.. function:: MATH_SIGN(i)

Returns the sign of the specified number.

:param float i: The number.

:return: The sign of the number (-1 for negative, 0 for zero, 1 for positive).

.. function:: MATH_POW(i)

Raises the base value to the specified power.

:param float i: The base value.

:return: The result of raising the base value to the power.

.. function:: MATH_ATAN2(y, x)

Returns the angle in radians between the positive x-axis and the vector defined by (x, y).

:param float y: The y-coordinate of the vector.
:param float x: The x-coordinate of the vector.

:return: The angle in radians.

.. function:: MATH_MAXI(a, b, c, d)

Returns the maximum value among the specified parameters. (could this be any size??)

:param float a: The first value to compare.
:param float b: The second value to compare.
:param float c: The third value to compare.
:param float d: The fourth value to compare.

:return: The maximum value among the parameters.
