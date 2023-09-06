getConnectedGamepads
====================

:doc:`/types/Script/index`::getConnectedGamepads

Returns the list of connected gamepads.

Declaration
-----------

.. code-block:: cpp

	std::vector<GamepadID> getConnectedGamepads();

Parameters
----------

None

Returns
-------

An `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_ of all connected :doc:`/types/GamepadID/index`\s.

If no gamepad is connected, the returned `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_ is empty.