getCursorPositionY
==================

:doc:`/types/WindowModuleInterface/index`::getCursorPositionY

Returns the mouse cursor vertical position.

Declaration
-----------

.. code-block:: cpp

	virtual int getCursorPositionY(WindowID windowID) = 0;

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
	  - The window to check the vertical cursor position on.

Returns
-------

The vertical position of the mouse cursor relative to the window, with 0 being the top edge of the window.