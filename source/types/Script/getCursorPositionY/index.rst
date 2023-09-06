getCursorPositionY
==================

:doc:`/types/Script/index`::getCursorPositionY

Returns the mouse cursor vertical position.

Declaration
-----------

.. code-block:: cpp

	int getCursorPositionY(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window to check the vertical cursor position on. By default, this window will be the main window.

Returns
-------

The vertical position of the mouse cursor relative to the window, with 0 being the top edge of the window.