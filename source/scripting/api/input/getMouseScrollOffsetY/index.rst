getMouseScrollOffsetY
=====================

Script::getMouseScrollOffsetY

Declaration
-----------

.. code-block:: cpp

	float getMouseScrollOffsetY(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - :doc:`/types/window_id/index`
	  - The window to check the vertical scroll wheel offset on. By default, this window will be the main window.

Returns
-------

The vertical mouse scroll offset between the last and current frame.

Notes
-----

The vertical mouse scroll often applies to a mouse scroll wheel.