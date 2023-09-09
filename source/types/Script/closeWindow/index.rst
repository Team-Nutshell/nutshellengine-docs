closeWindow
===========

:doc:`/types/Script/index`::closeWindow

Closes the window. Closing the main window closes the application.

Declaration
-----------

.. code-block:: cpp

	void closeWindow(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to close. By default, this window will be the main window.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.

Closing the main window will close the application.