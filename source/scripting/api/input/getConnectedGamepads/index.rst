getConnectedGamepads
====================

Script::getConnectedGamepads

Declaration
-----------

.. code-block:: cpp

	std::vector<GamepadID> getConnectedGamepads();

Parameters
----------

None

Returns
-------

An `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_ of all connected :doc:`/types/gamepad_id/index`\s.

If no gamepad is connected, the returned `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_ is empty.