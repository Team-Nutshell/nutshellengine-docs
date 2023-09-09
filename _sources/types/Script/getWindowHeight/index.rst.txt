getWindowHeight
===============

:doc:`/types/Script/index`::getWindowHeight

Returns the height of the window.

Declaration
-----------

.. code-block:: cpp

	int getWindowHeight(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to get the height of. By default, this window will be the main window.

Returns
-------

The height of the window.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.