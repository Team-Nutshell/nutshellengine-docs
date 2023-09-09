getGamepadName
==============

:doc:`/types/WindowModuleInterface/index`::getGamepadName

Returns the name of the gamepad.

Declaration
-----------

.. code-block:: cpp

	virtual std::string getGamepadName(GamepadID gamepadID) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - gamepadID
	  - :doc:`/types/GamepadID/index`
	  - The gamepad to get the name of.

Returns
-------

An `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_ containing the name of the gamepad.

The gamepad's name may be empty, this function will then return the empty string ``""``.