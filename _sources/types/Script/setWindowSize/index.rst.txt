setWindowSize
=============

:doc:`/types/Script/index`::setWindowSize

Sets the size of the window.

Declaration
-----------

.. code-block:: cpp

	void setWindowSize(int width, int height, WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - width
	  - int
	  - The new width of the window.
	* - height
	  - int
	  - The new height of the window.
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window to change the size of. By default, this window will be the main window.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.