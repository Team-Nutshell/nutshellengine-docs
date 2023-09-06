isWindowFullscreen
==================

:doc:`/scripting/script/index`::isWindowFullscreen

Checks if the window is in fullscreen.

Declaration
-----------

.. code-block:: cpp

	bool isWindowFullscreen(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to check the fullscreen mode of.

Returns
-------

``true`` if the window is in fullscreen, else, returns ``false``.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.