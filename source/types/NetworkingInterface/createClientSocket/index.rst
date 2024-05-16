createClientSocket
==================

:doc:`/types/NetworkingInterface/index`::createClientSocket

Creates a :doc:`/types/ClientSocket/index`.

Declaration
-----------

.. code-block:: cpp

	virtual ClientSocketInterface* createClientSocket(NetworkType networkType = NetworkType::UDP) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - networkType
	  - :doc:`/types/NetworkType/index`
	  - The network type.

Returns
-------

The memory address to a :doc:`/types/ClientSocket/index`.