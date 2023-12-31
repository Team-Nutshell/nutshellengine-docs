pop_front
=========

:doc:`/types/ThreadSafeQueue/index`::pop_front

Removes an element at the front of the queue.

Declaration
-----------

.. code-block:: cpp

	template<typename T>
	bool pop_front(T& element);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - element
	  - *T*\&
	  - The element at the front at the queue.

Returns
-------

``true`` if an element could be removed from the front of the queue, else, returns ``false``.