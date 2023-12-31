isWindowResizable
=================

:doc:`/types/Script/index`::isWindowResizable

Checks if the window can be manually resized.

Declaration
-----------

.. code-block:: cpp

	bool isWindowResizable(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to check the resizability of. By default, this window will be the main window.

Returns
-------

``true`` if the window is manually resizable, else, returns ``false``.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.

This function will only lock the user's ability to manually resize the window. The window will still be resizable with :doc:`/types/Script/setWindowSize/index`.