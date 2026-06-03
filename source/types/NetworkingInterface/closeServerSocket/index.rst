closeServerSocket
=================

:doc:`/types/NetworkingInterface/index`::closeServerSocket

Closes a :doc:`server socket </types/ServerSocketInterface/index>`.

Declaration
-----------

.. code-block:: cpp

	virtual void closeServerSocket(ServerSocketInterface* serverSocket) = 0;

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