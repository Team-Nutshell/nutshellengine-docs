closeServerSocket
=================

:doc:`/types/Script/index`::closeServerSocket

Closes a :doc:`server socket </types/ServerSocketInterface/index>`.

Declaration
-----------

.. code-block:: cpp

	void closeServerSocket(ServerSocketInterface* serverSocket);

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
	  - :doc:`/types/ServerSocketInterface/index`\*
	  - The memory address to the :doc:`server socket </types/ServerSocketInterface/index>` to close.

Returns
-------

None.

Notes
-----

If clients were connected to the ``serverSocket``, they will be disconnected.