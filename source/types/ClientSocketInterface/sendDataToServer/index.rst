sendDataToServer
================

:doc:`/types/ClientSocketInterface/index`::sendDataToServer

Sends data to a server.

Declaration
-----------

.. code-block:: cpp

	virtual void sendDataToServer(const void* data, size_t dataSize) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - data
	  - const void*
	  - The data to send to the server.
	* - dataSize
	  - size_t
	  - The size of the data to send to the server.

Returns
-------

None.

Notes
-----

:doc:`/types/Buffer/index` can be used to efficiently create the data to send to the server.