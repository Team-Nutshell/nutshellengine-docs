closeServerSocket
=================

:doc:`/types/Networking/index`::closeServerSocket

Closes a :doc:`/types/ServerSocket/index`.

Declaration
-----------

.. code-block:: cpp

	void closeServerSocket(ServerSocket* serverSocket);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - serverSocket
	  - :doc:`/types/ServerSocket/index`\*
	  - The memory address to the :doc:`/types/ServerSocket/index` to close.

Returns
-------

None.

Notes
-----

If clients were connected to the ``serverSocket``, they will be disconnected.