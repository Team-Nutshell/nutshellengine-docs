closeClientSocket
=================

:doc:`/scripting/script/index`::closeClientSocket

Closes a :doc:`/networking/ClientSocket/index`.

Declaration
-----------

.. code-block:: cpp

	void closeClientSocket(ClientSocket* clientSocket);

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
	  - :doc:`/networking/ClientSocket/index`\*
	  - The memory address to the :doc:`/networking/ClientSocket/index` to close.

Returns
-------

None.

Notes
-----

If ``clientSocket`` was connected to a server, it will be disconnected.