isWindowResizable
=================

:doc:`/types/WindowModuleInterface/index`::isWindowResizable

Checks if the window can be manually resized.

Declaration
-----------

.. code-block:: cpp

	virtual bool isWindowResizable(WindowID windowID) = 0;

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
	  - The window to check the resizability of.

Returns
-------

``true`` if the window is manually resizable, else, returns ``false``.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.

This function will only lock the user's ability to manually resize the window. The window will still be resizable with :doc:`/types/Script/setWindowSize/index`.