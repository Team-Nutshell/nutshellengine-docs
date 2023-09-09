setCursorPosition
=================

:doc:`/types/Script/index`::setCursorPosition

Sets the mouse cursor position.

Declaration
-----------

.. code-block:: cpp

	void setCursorPosition(int x, int y, WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - x
	  - int
	  - The horizontal position to set the mouse cursor to. 0 is the left edge of the window.
	* - y
	  - int
	  - The vertical position to set the mouse cursor to. 0 is the top edge of the window.
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window to set the position of the mouse cursor to. By default, this window will be the main window.

Returns
-------

None.