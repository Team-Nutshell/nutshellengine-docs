getMouseButtonState
===================

Script::getKeyState

Declaration
-----------

.. code-block:: cpp

	InputState getMouseButtonState(InputMouseButton mouseButton, WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - key
	  - :doc:`/types/input_mouse_button/index`
	  - The mouse button to check the state of.
	* - windowID
	  - :doc:`/types/window_id/index`
	  - The window to check the mouse button state on. By default, this window will be the main window.

Returns
-------

A :doc:`/types/input_mouse_button/index` containing the state of the mouse button.