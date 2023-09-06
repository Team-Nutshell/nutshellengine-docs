getGamepadStickAxisY
====================

:doc:`/scripting/script/index`::getGamepadStickAxisY

Returns the value of the stick's vertical axis, with -1.0 being up, 0.0 neutral and 1.0 down.

Declaration
-----------

.. code-block:: cpp

	float getGamepadStickAxisY(GamepadID gamepadID, InputGamepadStick stick);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - gamepadID
	  - :doc:`/types/GamepadID/index`
	  - The gamepad to get the vertical stick axis from.
	* - stick
	  - :doc:`/types/InputGamepadStick/index`
	  - The stick to get the vertical axis value from.

Returns
-------

A value between -1.0 and 1.0, with **0.0 being the neutral position**, **-1.0 being completely pushed up** and **1.0 being completely pushed down**.