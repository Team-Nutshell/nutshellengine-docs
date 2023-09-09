setWindowPosition
=================

:doc:`/types/WindowModuleInterface/index`::setWindowPosition

Sets the position of the window on the screen.

Declaration
-----------

.. code-block:: cpp

	virtual void setWindowPosition(WindowID windowID, int x, int y) = 0;

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
	  - The window to change the size of.
	* - x
	  - int
	  - The new horizontal position of the window.
	* - y
	  - int
	  - The new vertical position of the window.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.

The position's origin (0, 0) is the top-left corner of the main monitor.