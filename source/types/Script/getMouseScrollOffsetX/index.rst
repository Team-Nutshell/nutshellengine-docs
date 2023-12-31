getMouseScrollOffsetX
=====================

:doc:`/types/Script/index`::getMouseScrollOffsetX

Returns the horizontal mouse scroll offset between the last and current frame.

Declaration
-----------

.. code-block:: cpp

	float getMouseScrollOffsetX(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to check the horizontal scroll wheel offset on. By default, this window will be the main window.

Returns
-------

The horizontal mouse scroll offset between the last and current frame.

Notes
-----

The horizontal mouse scroll often applies to a laptop's trackpad. For a mouse scroll wheel, see :doc:`/types/Script/getMouseScrollOffsetY/index`.