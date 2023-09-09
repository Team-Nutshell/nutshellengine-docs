freeBlock
=========

:doc:`/types/BlockSuballocator/index`::freeBlock

Removes a block from the :doc:`/types/BlockSuballocator/index`.

Declaration
-----------

.. code-block:: cpp

	void freeBlock(size_t offset, size_t size)

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - offset
	  - size_t
	  - The block's offset to remove from the :doc:`/types/BlockSuballocator/index`.
	* - size
	  - size_t
	  - The block's size to remove from the :doc:`/types/BlockSuballocator/index`.

Returns
-------

None.