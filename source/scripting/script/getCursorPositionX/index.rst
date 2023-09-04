getCursorPositionX
==================

:doc:`/scripting/script/index`::getCursorPositionX

Declaration
-----------

.. code-block:: cpp

	int getCursorPositionX(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to check the horizontal cursor position on. By default, this window will be the main window.

Returns
-------

The horizontal position of the mouse cursor relative to the window, with 0 being the left edge of the window.