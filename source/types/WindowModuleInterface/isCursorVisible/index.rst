isCursorVisible
===============

:doc:`/types/WindowModuleInterface/index`::isCursorVisible

Checks if the cursor is visible.

Declaration
-----------

.. code-block:: cpp

	virtual bool isCursorVisible(WindowID windowID) = 0;

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
	  - The window to check the mouse cursor visibility of.

Returns
-------

``true`` if the mouse cursor is visible, else, returns ``false``.