createClientSocket
==================

:doc:`/types/Script/index`::createClientSocket

Creates a :doc:`client socket </types/ClientSocketInterface/index>`.

Declaration
-----------

.. code-block:: cpp

	ClientSocketInterface* createClientSocket(NetworkType networkType = NetworkType::UDP);

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

The memory address to a :doc:`client socket </types/ClientSocketInterface/index>`.