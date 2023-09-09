getWindowPositionY
==================

:doc:`/types/Script/index`::getWindowPositionY

Returns the vertical position of the window on the screen.

Declaration
-----------

.. code-block:: cpp

	int getWindowPositionY(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to get the vertical position of. By default, this window will be the main window.

Returns
-------

The vertical position of the window on the screen.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.

The position's origin on the window is the top-left corner of the window.

The position's origin (0, 0) on the screen is the top-left corner of the main monitor.