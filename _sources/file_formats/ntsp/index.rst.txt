.ntsp - Image Sampler
=====================

**.ntsp** is an **image sampler** format, made to mimick the :doc:`/types/ImageSampler/index` structure.

*.ntsp* is in the JSON format, and can be read and written using :doc:`/types/JSON/index`.

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	  - Possible values
	* - magFilter
	  - String
	  - The magnification filter.
	  -  
		 - "Linear"
		 - "Nearest"
		 - "Unknown"
	* - minFilter
	  - String
	  - The minification filter.
	  -  
		 - "Linear"
		 - "Nearest"
		 - "Unknown"
	* - mipmapFilter
	  - String
	  - The mipmap filter.
	  -  
		 - "Linear"
		 - "Nearest"
		 - "Unknown"
	* - addressModeU
	  - String
	  - The address mode on the U axis.
	  -  
		 - "Repeat"
		 - "MirroredRepeat"
		 - "ClampToEdge"
		 - "ClampToBorder"
		 - "Unknown"
	* - addressModeV
	  - String
	  - The address mode on the V axis.
	  -  
		 - "Repeat"
		 - "MirroredRepeat"
		 - "ClampToEdge"
		 - "ClampToBorder"
		 - "Unknown"
	* - addressModeW
	  - String
	  - The address mode on the W axis.
	  -  
		 - "Repeat"
		 - "MirroredRepeat"
		 - "ClampToEdge"
		 - "ClampToBorder"
		 - "Unknown"
	* - borderColor
	  - String
	  - The border color.
	  -  
		 - "FloatTransparentBlack"
		 - "IntTransparentBlack"
		 - "FloatOpaqueBlack"
		 - "IntOpaqueBlack"
		 - "FloatOpaqueWhite"
		 - "IntOpaqueWhite"
		 - "Unknown"
	* - anisotropyLevel
	  - Number
	  - The anisotropy level.
	  - Any number.
