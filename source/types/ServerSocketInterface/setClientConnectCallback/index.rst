setClientConnectCallback
========================

:doc:`/types/ServerSocketInterface/index`::setClientConnectCallback

Sets the function that will be called when a client connects to the server.

Declaration
-----------

.. code-block:: cpp

	virtual void setClientConnectCallback(std::function<void(ConnectedClientID)> callback) = 0;

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
	  - `std::function <https://en.cppreference.com/w/cpp/utility/functional/function>`_\<void(:doc:`/types/ConnectedClientID/index`)>
	  - The function that will be called when a client connects to the server.

Returns
-------

None.