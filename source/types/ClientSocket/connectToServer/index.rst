connectToServer
===============

:doc:`/types/ClientSocket/index`::connectToServer

Connects the client to a server.

Declaration
-----------

.. code-block:: cpp

	void connectToServer(const std::string& ipAddress, uint16_t port);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - ipAddress
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The IP address of the server to connect to.
	* - port
	  - uint16_t
	  - The port of the server to connect to.

Returns
-------

None.