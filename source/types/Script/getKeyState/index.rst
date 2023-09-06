getKeyState
===========

:doc:`/types/Script/index`::getKeyState

Returns the state of a keyboard key.

Declaration
-----------

.. code-block:: cpp

	InputState getKeyState(InputKeyboardKey key, WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - key
	  - :doc:`/types/InputKeyboardKey/index`
	  - The keyboard key to check the state of.
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window to check the key state on. By default, this window will be the main window.

Returns
-------

A :doc:`/types/InputKeyboardKey/index` containing the state of the keyboard key.