getMouseButtonState
===================

:doc:`/scripting/script/index`::getKeyState

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
	  - :doc:`/types/InputMouseButton/index`
	  - The mouse button to check the state of.
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window to check the mouse button state on. By default, this window will be the main window.

Returns
-------

A :doc:`/types/InputMouseButton/index` containing the state of the mouse button.