setWindowResizable
==================

:doc:`/types/WindowModuleInterface/index`::setWindowResizable

Enables or disables manual window resizing.

Declaration
-----------

.. code-block:: cpp

	virtual void setWindowResizable(WindowID windowID, bool resizable) = 0;

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
	  - The window to change the resizability of.
	* - resizable
	  - bool
	  - Resizable (``true``) or not resizable (``false``).

Returns
-------

None.