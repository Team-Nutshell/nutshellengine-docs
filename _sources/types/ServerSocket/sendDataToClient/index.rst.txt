sendDataToClient
================

:doc:`/types/ServerSocket/index`::sendDataToClient

Sends data to a client.

Declaration
-----------

.. code-block:: cpp

	void sendDataToClient(ConnectedClientID clientID, const void* data, size_t dataSize);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - clientID
	  - :doc:`/types/ConnectedClientID/index`
	  - The identifier of the client to send the data to.
	* - data
	  - const void*
	  - The data to send to the client.
	* - dataSize
	  - size_t
	  - The size of the data to send to the client.

Returns
-------

None.

Notes
-----

:doc:`/types/Buffer/index` can be used to efficiently create the data to send to the client.