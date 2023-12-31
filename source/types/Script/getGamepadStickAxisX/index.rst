getGamepadStickAxisX
====================

:doc:`/types/Script/index`::getGamepadStickAxisX

Returns the value of the stick's horizontal axis, with -1.0 being left, 0.0 neutral and 1.0 right.

Declaration
-----------

.. code-block:: cpp

	float getGamepadStickAxisX(GamepadID gamepadID, InputGamepadStick stick);

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
	  - The gamepad to get the horizontal stick axis from.
	* - stick
	  - :doc:`/types/InputGamepadStick/index`
	  - The stick to get the horizontal axis value from.

Returns
-------

A value between -1.0 and 1.0, with **0.0 being the neutral position**, **-1.0 being completely pushed left** and **1.0 being completely pushed right**.