isWindowBorderless
==================

:doc:`/types/Script/index`::isWindowBorderless

Checks if the window decorations are shown.

Declaration
-----------

.. code-block:: cpp

	bool isWindowBorderless(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to check the decorations of.

Returns
-------

``true`` if the window is borderless, else, returns ``false``.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.