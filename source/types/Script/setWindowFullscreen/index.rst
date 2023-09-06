setWindowFullscreen
===================

:doc:`/types/Script/index`::setWindowFullscreen

Puts the window in fullscreen or windowed.

Declaration
-----------

.. code-block:: cpp

	void setWindowFullscreen(bool fullscreen, WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - fullscreen
	  - bool
	  - Fullscreen (``true``) or windowed (``false``).
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window to change the fullscreen mode of.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.