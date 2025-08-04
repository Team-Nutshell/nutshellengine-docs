isWindowFocused
===============

:doc:`/types/WindowModuleInterface/index`::isWindowFocused

Checks if the window is focused.

Declaration
-----------

.. code-block:: cpp

	virtual bool isWindowFocused(WindowID windowID) = 0;

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
	  - The window to check.

Returns
-------

``true`` if the window is focused, else, returns ``false``.