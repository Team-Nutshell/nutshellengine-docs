setCursorVisibility
===================

:doc:`/types/WindowModuleInterface/index`::setCursorVisibility

Sets the mouse cursor's visibility.

Declaration
-----------

.. code-block:: cpp

	virtual void setCursorVisibility(WindowID windowID, bool visible) = 0;

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
	  - The window to set the mouse cursor visibility on.
	* - visible
	  - bool
	  - Cursor visibility.

Returns
-------

None.