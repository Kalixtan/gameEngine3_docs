
GameSystem Module
-----------------

This module provides access to various game system functionalities.

.. function:: GameSystem.getSimulationSpeed()

   Returns the simulation speed factor.

.. function:: GameSystem.trace(message)

   Outputs the specified message to the console.

   :param str message: The message to output.

.. function:: GameSystem.getProcess(processName)

Retrieves the process with the specified name.

:param str processName: The name of the process to retrieve.

:return: The process object, or null if no process with the specified name exists. (?)


.. function:: GameSystem.setAsPauseProcess(isPauseProcess, process)

Sets whether the specified process is a pause process or not.

:param bool isPauseProcess: Specifies whether the process should be set as a pause process.
:param obj process: The process object to set as a pause process.


.. function:: GameSystem.getEntityUpdateProcess()

Retrieves the entity update process.

:return: The entity update process object.


. function:: GameSystem.runProcess(processName)

Runs a new instance of the process with the specified name.

:param str processName: The name of the process to run.

:return: The process object.

.. function:: GameSystem.openConsole()

Opens the console.

Note: This function doesn't perform any action in the release build.

.. function:: GameSystem.getMSSincePlayStart()

Returns the number of milliseconds since the start of the play session.

:return: The number of milliseconds since play start.




.. function:: GameSystem.traceTick(message)

Outputs the specified message along with the current tick to the console. (?)

:param str message: The message to output.

.. variable:: Tick

Represents the current tick of the game system.

Example usage:

.. function:: GameSystem.getRandomReal(minValue, maxValue)

Generates a random real number between the specified minimum and maximum values.

:param float minValue: The minimum value.
:param float maxValue: The maximum value.

:return: A random real number between minValue and maxValue.


.. function:: GameSystem.getProcess(processName)

Retrieves the process with the specified name.

:param str processName: The name of the process to retrieve.

:return: The process object, or null if no process with the specified name exists.

Example usage:

lua

local proc = GameSystem.getProcess("Platformer_OnlineStartMenu");

.. function:: GameSystem.setAsPauseProcess(isPauseProcess, process)

Sets whether the specified process is a pause process or not.

:param bool isPauseProcess: Specifies whether the process should be set as a pause process.
:param obj process: The process object to set as a pause process.

Example usage:

lua

GameSystem.setAsPauseProcess(true, this.Process);

.. function:: GameSystem.getEntityUpdateProcess()

Retrieves the entity update process.

:return: The entity update process object.

Example usage:

lua

this.gameProcess = GameSystem.getEntityUpdateProcess();

.. function:: GameSystem.runProcess(processName)

Runs a new instance of the process with the specified name.

:param str processName: The name of the process to run.

:return: The process object.

Example usage:

lua

local proc = GameSystem.runProcess("Platformer_OnlineGriefMenu");

.. function:: GameSystem.openConsole()

Opens the console.

Note: This function doesn't perform any action in the given code snippet.

.. function:: GameSystem.getMSSincePlayStart()

Returns the number of milliseconds since the start of the play session.

:return: The number of milliseconds since play start.

Example usage:

lua

local msSincePlayStart = GameSystem.getMSSincePlayStart();

.. function:: GameSystem.traceTick(message)

Outputs the specified message along with the current tick to the console.

:param str message: The message to output.

Example usage:

lua

GameSystem.traceTick("GET IN HERE!");

.. variable:: Tick

Represents the current tick of the game system.

Example usage:

lua

local currentTick = GameSystem.Tick;

.. function:: GameSystem.getRandomReal(minValue, maxValue)

Generates a random real number between the specified minimum and maximum values.

:param float minValue: The minimum value.
:param float maxValue: The maximum value.

:return: A random real number between minValue and maxValue.



.. function:: GameSystem.getRandomInteger(minValue, maxValue)

Generates a random integer between the specified minimum and maximum values.

:param int minValue: The minimum value.
:param int maxValue: The maximum value.

:return: A random integer between minValue and maxValue.


.. function:: GameSystem.resetSimulationTimer()

Resets the simulation timer.


