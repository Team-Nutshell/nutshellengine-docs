setCursorVisibility
===================

:doc:`/scripting/script/index`::setCursorVisibility

Declaration
-----------

.. code-block:: cpp

	void setCursorVisibility(bool visible, WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - visible
	  - bool
	  - Cursor visibility.
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window to set the mouse cursor visibility on. By default, this window will be the main window.

Returns
-------

None.