
Input Module
------------

This module provides functions for handling input events.

.. function:: Input.isKeyPressed(keyCode)

   Returns true if the specified key is currently pressed.

   :param int keyCode: The key code of the key.
   
  :return: is the key pressed.

.. function:: Input.isAltPressed()

   Returns true if the Alt key is currently pressed. [ This doesnt work in any public build ]

  :return: is the key pressed.

.. function:: Input.isControlPressed()

   Returns true if the Control key is currently pressed. [ This doesnt work in any public build ]

  :return: is the key pressed.

.. function:: Input.isShiftPressed()

   Returns true if the Shift key is currently pressed. [ This doesnt work in any public build ]

  :return: is the key pressed.

.. function:: Input.getFrontTouchCount()

  Returns the number of currently active front touch points.

  :return: The number of active touch points.


.. function:: Input.getJoystickAxis(id, input)

    Retrieves the value of the specified joystick axis for the given controller index.

    :param int id: The index of the controller (1-6).
    :param int input: The input specifier indicating the joystick axis to retrieve.

    :return: The value of the specified joystick axis.
    
    
.. function:: Input.getFrontTouchPos(touchID)

    Returns the position of the front touch with the specified touch ID.

    :param int touchID: The ID of the touch.

    :return: The position of the touch as a vector.

.. function:: Input.getBackTouchPos(touchID)

    Returns the position of the back touch with the specified touch ID.

    :param int touchID: The ID of the touch.

    :return: The position of the touch as a vector.

.. function:: Input.enableShaking()

    Enables shaking input.

.. function:: Input.disableShaking()

    Disables shaking input.

.. function:: Input.getIsShaking()

    Returns true if shaking input is enabled.

.. function:: Input.getWasTouchTap(touchID)

    Returns true if the touch with the specified touch ID was a tap (quick touch and release).

    :param int touchID: The ID of the touch.

.. function:: Input.getIsTouchMoving(panelType, touchID)

    Returns true if the touch with the specified touch ID is moving on the specified panel type.

    :param int panelType: The panel type (PANEL_FRONT or PANEL_BACK).
    :param int touchID: The ID of the touch.

.. function:: Input.enableBackPanel()

    Enables input on the back panel.

.. function:: Input.disableBackPanel()

    Disables input on the back panel.

.. function:: Input.getMousePosVec()

    Returns the position of the mouse cursor as a vector.

.. function:: Input.getIsTouchHold(pulseID)

    Returns true if the pulse with the specified ID is being held.

    :param int pulseID: The ID of the pulse.

.. function:: Input.isControllerPresent()

    Returns true if a controller is present.

.. function:: Input.openIME(table)

    Opens the Input Method Editor (IME) with the specified options.

    :param table: A table containing the options for the IME.

.. function:: Input.getIMEStatus()

    Returns the status of the Input Method Editor (IME).

.. function:: Input.getIMEResults()

    Returns the results of the Input Method Editor (IME).

.. function:: Input.getStringIME()

    Returns the input string from the Input Method Editor (IME).
