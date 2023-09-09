Image
=====

Declaration
-----------

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - width
	  - uint32_t
	  - The image's width.
	* - height
	  - uint32_t
	  - The image's height.
	* - format
	  - :doc:`/types/ImageFormat/index`
	  - The image's format detailing the layout in memory.
	* - colorSpace
	  - :doc:`/types/ImageColorSpace/index`
	  - The image's color space.
	* - data
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<uint8_t>
	  - The image's content, according to its ``format``.