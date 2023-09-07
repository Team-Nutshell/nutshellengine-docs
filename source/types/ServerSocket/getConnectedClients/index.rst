getConnectedClients
===================

:doc:`/types/ServerSocket/index`::getConnectedClients

Returns information about all the clients connected to the server.

Declaration
-----------

.. code-block:: cpp

	const std::unordered_map<ConnectedClientID, ConnectedClient>& getConnectedClients();

Parameters
----------

None.

Returns
-------

An `std::unordered_map <https://en.cppreference.com/w/cpp/container/unordered_map>`_ using the :doc:`/types/ConnectedClientID/index` as a key and :doc:`/types/ConnectedClient/index` as the value, for all clients connected to the server.