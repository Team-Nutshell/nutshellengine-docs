Font
====

Declaration
-----------

.. code-block:: cpp

	struct Font {
		Image* image = nullptr;
		ImageSamplerFilter imageSamplerFilter = ImageSamplerFilter::Unknown;
		std::unordered_map<char, FontGlyph> glyphs;
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
	* - image
	  - :doc:`/types/image/index`\*
	  - The pointer to the image containing the glyphs.
	* - imageSamplerFilter
	  - :doc:`/types/image_sampler_filter/index`
	  - The sampler filter to use when drawing a text with this font.
	* - glyphs
	  - `std::unordered_map <https://en.cppreference.com/w/cpp/container/unordered_map>`_\<char, :doc:`/types/font_glyph/index`>
	  - A map containing information about each glyph.