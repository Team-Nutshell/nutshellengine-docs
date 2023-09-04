write
=====

:doc:`/utils/Buffer/index`::write

Declaration
-----------

.. code-block:: cpp

	void write(const std::byte* dataToWrite, size_t size);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - data
	  - const `std::byte <https://en.cppreference.com/w/cpp/types/byte>`_\*
	  - The memory address of the data to write in the :doc:`/utils/Buffer/index`.
	* - size
	  - size_t
	  - The size of the ``data`` to write in the :doc:`/utils/Buffer/index`.

Returns
-------

None.

Notes
-----

This function will resize the :doc:`/utils/Buffer/index` if :math:`(cursor + size) > getSize()`.

The cursor is then advanced by the size of the written data, but its position can be set using :doc:`/utils/Buffer/setCursorPosition/index`.