setWindowResizable
==================

:doc:`/scripting/script/index`::setWindowResizable

Enables or disables manual window resizing.

Declaration
-----------

.. code-block:: cpp

	void setWindowResizable(bool resizable, WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - resizable
	  - bool
	  - Resizable (``true``) or not resizable (``false``).
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window to change the resizability of.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.