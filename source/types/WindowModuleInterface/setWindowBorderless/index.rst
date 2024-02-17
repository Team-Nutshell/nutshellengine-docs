setWindowBorderless
===================

:doc:`/types/WindowModuleInterface/index`::setWindowBorderless

Removes or adds the window decorations.

Declaration
-----------

.. code-block:: cpp

	virtual void setWindowBorderless(WindowID windowID, bool borderless) = 0;

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
	  - The window to change the decorations of.
	* - borderless
	  - bool
	  - Borderless (``true``) or with decorations (``false``).

Returns
-------

None.