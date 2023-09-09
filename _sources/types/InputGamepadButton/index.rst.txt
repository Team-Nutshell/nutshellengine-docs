InputGamepadButton
==================

Declaration
-----------

.. code-block:: cpp

	enum class InputGamepadButton {
		Any, // Any gamepad button
		Face1, // First face button
		Face2, // Second face button
		Face3, // Third face button
		Face4, // Fourth face button
		Start, // Start face button
		Select, // Select face button
		Guide, // Guide face button
		LeftStick, // Left stick button
		RightStick, // Right stick button
		LeftBumper, // Left shoulder button
		RightBumper, // Right shoulder button
		DPadLeft, // Directional pad left button
		DPadRight, // Directional pad right button
		DPadUp, // Directional pad up button
		DPadDown // Directional pad down button
	};

Notes
-----

The gamepad's layout depends on the type of gamepad used.

Generally, ``Face1`` is the button to confirm, while ``Face2`` is the button to cancel.

.. image:: /assets/gamepad.png

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Number
	  - Value
	  - Description
	* - 1
	  - Face1
	  - The "confirm" face button.
	* - 2
	  - Face2
	  - The "cancel" face button.
	* - 3
	  - Face3
	  - The face button next to ``Face1``.
	* - 4
	  - Face4
	  - The face button next to ``Face2``.
	* - 5
	  - Start
	  - The "pause" button.
	* - 6
	  - Select
	  - The button next to, or opposed to, ``Start``.
	* - 7
	  - Guide
	  - The button used to open a platform-specific menu.
	* - 8
	  - LeftStick
	  - The button on the left stick.
	* - 9
	  - RightStick
	  - The button on the right stick.
	* - 10
	  - LeftBumper
	  - The left shoulder button.
	* - 11
	  - RightBumper
	  - The right shoulder button.
	* - 12
	  - DPadLeft
	  - The directional-pad left button.
	* - 13
	  - DPadRight
	  - The directional-pad right button.
	* - 14
	  - DPadUp
	  - The directional-pad up button.
	* - 15
	  - DPadDown
	  - The directional-pad down button.

The left and right triggers are not available here as they are **analogic** buttons.