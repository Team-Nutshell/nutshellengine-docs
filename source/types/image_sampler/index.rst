ImageSampler
============

Declaration
-----------

.. code-block:: cpp

	struct ImageSampler {
		ImageSamplerFilter magFilter = ImageSamplerFilter::Unknown;
		ImageSamplerFilter minFilter = ImageSamplerFilter::Unknown;
		ImageSamplerFilter mipmapFilter = ImageSamplerFilter::Unknown;
		ImageSamplerAddressMode addressModeU = ImageSamplerAddressMode::Unknown;
		ImageSamplerAddressMode addressModeV = ImageSamplerAddressMode::Unknown;
		ImageSamplerAddressMode addressModeW = ImageSamplerAddressMode::Unknown;
		ImageSamplerBorderColor borderColor = ImageSamplerBorderColor::Unknown;
		float anisotropyLevel = 0.0f;
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
	* - magFilter
	  - :doc:`/types/image_sampler_filter/index`
	  - The sampler's magnification filter.
	* - minFilter
	  - :doc:`/types/image_sampler_filter/index`
	  - The sampler's minification filter.
	* - mipmapFilter
	  - :doc:`/types/image_sampler_filter/index`
	  - The sampler's mip map filter.
	* - addressModeU
	  - :doc:`/types/image_sampler_address_mode/index`
	  - The sampler's address mode on U.
	* - addressModeV
	  - :doc:`/types/image_sampler_address_mode/index`
	  - The sampler's address mode on V.
	* - addressModeW
	  - :doc:`/types/image_sampler_address_mode/index`
	  - The sampler's address mode on W.
	* - borderColor
	  - :doc:`/types/image_sampler_border_color/index`
	  - The sampler's border color if one of the address mode is ``ClampToBorder``.
	* - anisotropyLevel
	  - float
	  - The anisotropy level.