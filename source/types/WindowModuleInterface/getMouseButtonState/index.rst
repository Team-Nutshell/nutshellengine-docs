getMouseButtonState
===================

:doc:`/types/WindowModuleInterface/index`::getMouseButtonState

Returns the state of a mouse button.

Declaration
-----------

.. code-block:: cpp

	virtual InputState getMouseButtonState(WindowID windowID, InputMouseButton mouseButton) = 0;

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
	  - The window to check the mouse button state on.
	* - mouseButton
	  - :doc:`/types/InputMouseButton/index`
	  - The mouse button to check the state of.

Returns
-------

A :doc:`/types/InputMouseButton/index` containing the state of the mouse button.