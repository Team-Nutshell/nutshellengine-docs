getKeyState
===========

:doc:`/types/WindowModuleInterface/index`::getKeyState

Returns the state of a keyboard key.

Declaration
-----------

.. code-block:: cpp

	virtual InputState getKeyState(WindowID windowID, InputKeyboardKey key) = 0;

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
	  - The window to check the key state on.
	* - key
	  - :doc:`/types/InputKeyboardKey/index`
	  - The keyboard key to check the state of.

Returns
-------

A :doc:`/types/InputKeyboardKey/index` containing the state of the keyboard key.