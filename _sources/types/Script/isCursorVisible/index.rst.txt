isCursorVisible
===============

:doc:`/types/Script/index`::isCursorVisible

Checks if the cursor is visible.

Declaration
-----------

.. code-block:: cpp

	bool isCursorVisible(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to check the mouse cursor visibility of. By default, this window will be the main window.

Returns
-------

``true`` if the mouse cursor is visible, else, returns ``false``.