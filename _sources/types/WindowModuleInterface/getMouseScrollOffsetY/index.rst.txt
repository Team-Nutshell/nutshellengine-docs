getMouseScrollOffsetY
=====================

:doc:`/types/WindowModuleInterface/index`::getMouseScrollOffsetY

Returns the vertical mouse scroll offset between the last and current frame.

Declaration
-----------

.. code-block:: cpp

	virtual float getMouseScrollOffsetY(WindowID windowID) = 0;

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
	  - The window to check the vertical scroll wheel offset on.

Returns
-------

The vertical mouse scroll offset between the last and current frame.

Notes
-----

The vertical mouse scroll often applies to a mouse scroll wheel.