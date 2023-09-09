closeWindow
===========

:doc:`/types/WindowModuleInterface/index`::closeWindow

Closes the window. Closing the main window closes the application.

Declaration
-----------

.. code-block:: cpp

	virtual void closeWindow(WindowID windowID) = 0;

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
	  - The window to close.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.

Closing the main window will close the application.