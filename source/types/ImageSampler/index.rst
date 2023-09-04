ImageSampler
============

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - magFilter
	  - :doc:`/types/ImageSamplerFilter/index`
	  - The sampler's magnification filter.
	* - minFilter
	  - :doc:`/types/ImageSamplerFilter/index`
	  - The sampler's minification filter.
	* - mipmapFilter
	  - :doc:`/types/ImageSamplerFilter/index`
	  - The sampler's mip map ImageSamplerFilter.
	* - addressModeU
	  - :doc:`/types/ImageSamplerAddressMode/index`
	  - The sampler's address mode on U.
	* - addressModeV
	  - :doc:`/types/ImageSamplerAddressMode/index`
	  - The sampler's address mode on V.
	* - addressModeW
	  - :doc:`/types/ImageSamplerAddressMode/index`
	  - The sampler's address mode on W.
	* - borderColor
	  - :doc:`/types/ImageSamplerBorderColor/index`
	  - The sampler's border color if one of the address mode is ``ClampToBorder``.
	* - anisotropyLevel
	  - float
	  - The anisotropy level.