getWindowHeight
===============

:doc:`/types/WindowModuleInterface/index`::getWindowHeight

Returns the height of the window.

Declaration
-----------

.. code-block:: cpp

	virtual int getWindowWidth(WindowID windowID) = 0;

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
	  - The window to get the height of.

Returns
-------

The height of the window.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.