createServerSocket
==================

:doc:`/types/NetworkingInterface/index`::createServerSocket

Creates a :doc:`/types/ServerSocket/index`.

Declaration
-----------

.. code-block:: cpp

	virtual ServerSocketInterface* createServerSocket(uint16_t port, NetworkType networkType = NetworkType::UDP) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - port
	  - uint16_t
	  - The network port to assign to the server.
	* - networkType
	  - :doc:`/types/NetworkType/index`
	  - The network type.

Returns
-------

The memory address to a :doc:`/types/ServerSocket/index`.