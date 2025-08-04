isWindowFocused
===============

:doc:`/types/Script/index`::isWindowFocused

Checks if the window is focused.

Declaration
-----------

.. code-block:: cpp

	bool isWindowFocused(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to check. By default, this window will be the main window.

Returns
-------

``true`` if the window is focused, else, returns ``false``.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.