getGamepadButtonState
=====================

Script::getGamepadButtonState

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
	  - :doc:`/types/gamepad_id/index`
	  - The gamepad to get the button state from.
	* - button
	  - :doc:`/types/input_gamepad_button/index`
	  - The button to get the state from.

Returns
-------

An :doc:`/types/input_state/index` containing the state of the gamepad button.

Left and right triggers being analogic inputs, they are not covered by this function, see :doc:`/scripting/api/input/getGamepadLeftTrigger/index` and :doc:`/scripting/api/input/getGamepadRightTrigger/index`.