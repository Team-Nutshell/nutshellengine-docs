execute
=======

:doc:`/utils/Octree/index`::execute

 Executes a function on all elements of the Octree.

Declaration
-----------

.. code-block:: cpp

	void execute(const std::function<void(std::vector<Entry>&)>& operation);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - operation
	  - const `std::function <https://en.cppreference.com/w/cpp/utility/functional/function>`_\<void(`std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<:doc:`/utils/Octree/Entry/index`>&)>&
	  - The function that will be executed on each of the :doc:`/utils/Octree/index`'s leaves.

Returns
-------

None.