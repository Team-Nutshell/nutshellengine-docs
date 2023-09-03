Image
=====

Declaration
-----------

.. code-block:: cpp

	struct Image {
		uint32_t width = 0;
		uint32_t height = 0;
		ImageFormat format = ImageFormat::Unknown;
		ImageColorSpace colorSpace = ImageColorSpace::Unknown;
		std::vector<uint8_t> data;
	};

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
	  - :doc:`/types/image_format/index`
	  - The image's format detailing the layout in memory.
	* - colorSpace
	  - :doc:`/types/image_color_space/index`
	  - The image's color space.
	* - data
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<uint8_t>
	  - The image's content, according to its ``format``.