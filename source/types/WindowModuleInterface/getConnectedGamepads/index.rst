getConnectedGamepads
====================

:doc:`/types/WindowModuleInterface/index`::getConnectedGamepads

Returns the list of connected gamepads.

Declaration
-----------

.. code-block:: cpp

	virtual std::vector<GamepadID> getConnectedGamepads() = 0;

Parameters
----------

None

Returns
-------

An `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_ of all connected :doc:`GamepadIDs </types/GamepadID/index>`.

If no gamepad is connected, the returned `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_ is empty.