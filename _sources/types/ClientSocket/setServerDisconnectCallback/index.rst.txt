setServerDisconnectCallback
===========================

:doc:`/types/ClientSocket/index`::setServerDisconnectCallback

Sets the function that will be called when the client gets disconnected from the server.

Declaration
-----------

.. code-block:: cpp

	void setServerDisconnectCallback(std::function<void()> callback);

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
	  - `std::function <https://en.cppreference.com/w/cpp/utility/functional/function>`_\<void()>
	  - The function that will be called when the client gets disconnected from the server.

Returns
-------

None.