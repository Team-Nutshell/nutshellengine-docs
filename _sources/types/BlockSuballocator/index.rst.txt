BlockSuballocator
=================

BlockSuballocator is an helper structure used to simulate resource block suballocations.

Functions
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/BlockSuballocator/constructor/index`
	  - Constructs a :doc:`/types/BlockSuballocator/index` with a given size. 
	* - :doc:`/types/BlockSuballocator/addBlock/index`
	  - Adds a block to the :doc:`/types/BlockSuballocator/index` and returns its offset.
	* - :doc:`/types/BlockSuballocator/freeBlock/index`
	  - Removes a block from the :doc:`/types/BlockSuballocator/index`.

.. toctree::
	:hidden:

	./constructor/index.rst
	./addBlock/index.rst
	./freeBlock/index.rst