getWindowPositionX
==================

:doc:`/types/WindowModuleInterface/index`::getWindowPositionX

Returns the horizontal position of the window on the screen.

Declaration
-----------

.. code-block:: cpp

	virtual int getWindowPositionX(WindowID windowID) = 0;

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
	  - The window to get the horizontal position of.

Returns
-------

The horizontal position of the window on the screen.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.

The position's origin on the window is the top-left corner of the window.

The position's origin (0, 0) on the screen is the top-left corner of the main monitor.