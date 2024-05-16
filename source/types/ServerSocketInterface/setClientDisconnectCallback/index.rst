setClientDisconnectCallback
===========================

:doc:`/types/ServerSocketInterface/index`::setClientDisconnectCallback

Sets the function that will be called when a client disconnects from the server.

Declaration
-----------

.. code-block:: cpp

	virtual void setClientDisconnectCallback(std::function<void(ConnectedClientID)> callback) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - callback
	  - `std::function <https://en.cppreference.com/w/cpp/utility/functional/function>`_\<void(:doc:`/types/ConnectedClientID/index`)>
	  - The function that will be called when a client disconnects from the server.

Returns
-------

None.