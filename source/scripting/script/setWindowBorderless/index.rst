setWindowBorderless
===================

:doc:`/scripting/script/index`::setWindowBorderless

Removes or adds the window decorations.

Declaration
-----------

.. code-block:: cpp

	void setWindowBorderless(bool borderless, WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - borderless
	  - bool
	  - Borderless (``true``) or with decorations (``false``).
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window to change the decorations of.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.