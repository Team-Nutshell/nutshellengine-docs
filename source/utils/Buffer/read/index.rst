read
====

:doc:`/utils/Buffer/index`::read

Reads content from a Buffer.

Declaration
-----------

.. code-block:: cpp

	size_t read(std::byte* dataToRead, size_t size);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - dataToRead
	  - `std::byte <https://en.cppreference.com/w/cpp/types/byte>`_\*
	  - A pointer to get the data read from the :doc:`/utils/Buffer/index`.
	* - size
	  - size_t
	  - The amount of data to read from the :doc:`/utils/Buffer/index`.

Returns
-------

The actual size of the data read from the :doc:`/utils/Buffer/index`.

This actual data size is calculated this way:

:math:`actualSize = \begin{cases} getSize() - cursor, & (cursor + size) > getSize() \\ size, & otherwise \end{cases}`

The cursor is then advanced by this actual size, but its position can be set using :doc:`/utils/Buffer/setCursorPosition/index`.