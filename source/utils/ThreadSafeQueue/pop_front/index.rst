pop_front
=========

:doc:`/utils/ThreadSafeQueue/index`::pop_front

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