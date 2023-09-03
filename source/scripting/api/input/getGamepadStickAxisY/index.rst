getGamepadStickAxisY
====================

Script::getGamepadStickAxisY

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
	  - :doc:`/types/gamepad_id/index`
	  - The gamepad to get the vertical stick axis from.
	* - stick
	  - :doc:`/types/input_gamepad_stick/index`
	  - The stick to get the vertical axis value from.

Returns
-------

A value between -1.0 and 1.0, with **0.0 being the neutral position**, **-1.0 being completely pushed up** and **1.0 being completely pushed down**.