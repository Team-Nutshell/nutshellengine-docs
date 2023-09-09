addBlock
========

:doc:`/types/BlockSuballocator/index`::addBlock

Adds a block to the :doc:`/types/BlockSuballocator/index` and returns its offset.

Declaration
-----------

.. code-block:: cpp

	size_t addBlock(size_t size);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - size
	  - size_t
	  - The block's size to add to the :doc:`/types/BlockSuballocator/index`.

Returns
-------

The block's offset in the :doc:`/types/BlockSuballocator/index`.