getCursorPositionX
==================

:doc:`/types/WindowModuleInterface/index`::getCursorPositionX

Returns the mouse cursor horizontal position.

Declaration
-----------

.. code-block:: cpp

	virtual int getCursorPositionX(WindowID windowID) = 0;

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
	  - The window to check the horizontal cursor position on.

Returns
-------

The horizontal position of the mouse cursor relative to the window, with 0 being the left edge of the window.