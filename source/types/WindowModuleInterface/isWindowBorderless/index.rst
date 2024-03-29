isWindowBorderless
==================

:doc:`/types/WindowModuleInterface/index`::isWindowBorderless

Checks if the window decorations are shown.

Declaration
-----------

.. code-block:: cpp

	virtual bool isWindowBorderless(WindowID windowID) = 0;

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
	  - The window to check the decorations of.

Returns
-------

``true`` if the window is borderless, else, returns ``false``.