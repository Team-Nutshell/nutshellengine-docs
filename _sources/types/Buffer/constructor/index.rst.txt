Buffer
======

:doc:`/types/Buffer/index`::Buffer

Constructs a Buffer.

Declaration
-----------

.. code-block:: cpp

	Buffer();

Parameters
----------

None.

Returns
-------

An empty :doc:`/types/Buffer/index`.

====

Declaration
-----------

.. code-block:: cpp

	explicit Buffer(size_t size);

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
	  - The initial :doc:`/types/Buffer/index` size.

Returns
-------

An empty :doc:`/types/Buffer/index` with a pre-allocated memory.

====

Declaration
-----------

.. code-block:: cpp

	Buffer(const std::byte* data, size_t size);

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
	  - The memory address of the data to copy.
	* - size
	  - size_t
	  - The size of the ``data`` to copy.

Returns
-------

A :doc:`/types/Buffer/index` filled with ``data``.

====

Declaration
-----------

.. code-block:: cpp

	Buffer(const Buffer& other);

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
	  - const :doc:`/types/Buffer/index`\&
	  - The :doc:`/types/Buffer/index` to copy.

Returns
-------

A copy of the :doc:`/types/Buffer/index`.