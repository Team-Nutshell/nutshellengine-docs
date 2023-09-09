.ntim - Image
=============

**.ntim** is an **image** format, like *.png or .jpg*, but made to mimick the :doc:`/types/Image/index` structure. The data is **uncompressed** so it is only recommended to use it in small programs.

*.ntim* is in the JSON format, and can be read and written using :doc:`/types/JSON/index`.

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	  - Possible values
	* - width
	  - Number
	  - The width of the image.
	  - Any number.
	* - height
	  - Number
	  - The width of the image.
	  - Any number.
	* - format
	  - String
	  - The image format.
	  -  
		 - "R8"
		 - "R8G8"
		 - "R8G8B8"
		 - "R8G8B8A8"
		 - "R16"
		 - "R16G16"
		 - "R16G16B16"
		 - "R16G16B16A16"
		 - "R32"
		 - "R32G32"
		 - "R32G32B32"
		 - "R32G32B32A32"
		 - "Unknown"
	* - colorSpace
	  - String
	  - The image color space.
	  -  
		 - "Linear"
		 - "SRGB"
		 - "Unknown"
	* - data
	  - Array of Numbers
	  - The content of the image.
	  - Any array of any numbers.
