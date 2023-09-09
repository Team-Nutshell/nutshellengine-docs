setCursorPosition
=================

:doc:`/types/WindowModuleInterface/index`::setCursorPosition

Sets the mouse cursor position.

Declaration
-----------

.. code-block:: cpp

	virtual void setCursorPosition(WindowID windowID, int x, int y) = 0;

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
	  - The window to set the position of the mouse cursor to.
	* - x
	  - int
	  - The horizontal position to set the mouse cursor to. 0 is the left edge of the window.
	* - y
	  - int
	  - The vertical position to set the mouse cursor to. 0 is the top edge of the window.

Returns
-------

None.