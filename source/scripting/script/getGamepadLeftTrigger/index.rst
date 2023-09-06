getGamepadLeftTrigger
=====================

:doc:`/scripting/script/index`::getGamepadLeftTrigger

Returns the value of the stick's left trigger, with 0.0 being neutral and 1.0 being fully pressed.

Declaration
-----------

.. code-block:: cpp

	float getGamepadLeftTrigger(GamepadID gamepadID);

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
	  - The gamepad to get the left trigger value from.

Returns
-------

A value between 0.0 and 1.0 where 0.0 means that the trigger is not pushed and 1.0 means that the trigger is completely pushed.