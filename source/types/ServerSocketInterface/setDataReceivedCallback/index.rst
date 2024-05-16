setDataReceivedCallback
=======================

:doc:`/types/ServerSocketInterface/index`::setDataReceivedCallback

Sets the function that will be called when data is received from any client.

Declaration
-----------

.. code-block:: cpp

	virtual void setDataReceivedCallback(std::function<void(ConnectedClientID, void*, size_t)> callback) = 0;

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
	  - `std::function <https://en.cppreference.com/w/cpp/utility/functional/function>`_\<void(:doc:`/types/ConnectedClientID/index`, void*, size_t)>
	  - The function that will be called when data is received from any client.

Returns
-------

None.

Notes
-----

:doc:`/types/Buffer/index` can be used to efficiently parse the data received from the client.