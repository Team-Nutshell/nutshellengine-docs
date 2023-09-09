getWindowWidth
==============

:doc:`/types/WindowModuleInterface/index`::getWindowWidth

Returns the width of the window.

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
	  - The window to get the width of.

Returns
-------

The width of the window.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.