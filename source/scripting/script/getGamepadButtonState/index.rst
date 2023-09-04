getGamepadButtonState
=====================

:doc:`/scripting/script/index`::getGamepadButtonState

Declaration
-----------

.. code-block:: cpp

	InputState getGamepadButtonState(GamepadID gamepadID, InputGamepadButton button);

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
	  - The gamepad to get the button state from.
	* - button
	  - :doc:`/types/InputGamepadButton/index`
	  - The button to get the state from.

Returns
-------

An :doc:`/types/InputState/index` containing the state of the gamepad button.

Left and right triggers being analogic inputs, they are not covered by this function, see :doc:`/scripting/script/getGamepadLeftTrigger/index` and :doc:`/scripting/script/getGamepadRightTrigger/index`.