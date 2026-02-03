Font
====

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
	  - :doc:`/types/ImageFormat/index`\*
	  - The pointer to the image containing the glyphs.
	* - imageSamplerFilter
	  - :doc:`/types/ImageSamplerFilter/index`
	  - The sampler filter to use when drawing a text with this font.
	* - height
	  - float
	  - The pixel height of the font.
	* - glyphs
	  - `std::unordered_map <https://en.cppreference.com/w/cpp/container/unordered_map>`_\<char, :doc:`/types/FontGlyph/index`>
	  - A map containing information about each glyph.