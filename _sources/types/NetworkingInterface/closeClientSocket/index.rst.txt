closeClientSocket
=================

:doc:`/types/NetworkingInterface/index`::closeClientSocket

Closes a :doc:`/types/ClientSocket/index`.

Declaration
-----------

.. code-block:: cpp

	virtual void closeClientSocket(ClientSocketInterface* clientSocket) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - clientSocket
	  - :doc:`/types/ClientSocketInterface/index`\*
	  - The memory address to the :doc:`/types/ClientSocket/index` to close.

Returns
-------

None.

Notes
-----

If ``clientSocket`` was connected to a server, it will be disconnected.