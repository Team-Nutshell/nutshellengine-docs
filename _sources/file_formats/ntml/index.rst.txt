.ntml - Material
================

**.ntml** is a **Material** format, made to mimick the :doc:`/types/Material/index` structure.

*.ntml* is in the JSON format, and can be read and written using :doc:`/types/JSON/index`.

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	  - Possible values
	* - diffuse
	  - Object
	  - The diffuse parameter.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - texture
			  - Object
			  - The image and image sampler to use.
			  - .. list-table::
					:width: 100%
					:header-rows: 1
					:class: code-table

					* - Name
					  - Type
					  - Description
					  - Possible values
					* - imagePath
					  - String
					  - The path to the diffuse texture.
					  - A path to an image.
					* - imageSamplerPath
					  - String
					  - The path to the :doc:`/file_formats/ntsp/index`.
					  - A path to an image sampler.
			* - color
			  - Array of Number
			  - The diffuse color. The 4th component is the material opacity. Is used if no texture is specified.
			  - Any array of 4 numbers, between 0.0 and 1.0.
	* - normal
	  - Object
	  - The normal paramater.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - texture
			  - Object
			  - The image and image sampler to use.
			  - .. list-table::
					:width: 100%
					:header-rows: 1
					:class: code-table

					* - Name
					  - Type
					  - Description
					  - Possible values
					* - imagePath
					  - String
					  - The path to the normal texture.
					  - A path to an image.
					* - imageSamplerPath
					  - String
					  - The path to the :doc:`/file_formats/ntsp/index`.
					  - A path to an image sampler.
	* - metalness
	  - Object
	  - The metalness parameter.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - texture
			  - Object
			  - The image and image sampler to use.
			  - .. list-table::
					:width: 100%
					:header-rows: 1
					:class: code-table

					* - Name
					  - Type
					  - Description
					  - Possible values
					* - imagePath
					  - String
					  - The path to the metalness texture.
					  - A path to an image.
					* - imageSamplerPath
					  - String
					  - The path to the :doc:`/file_formats/ntsp/index`.
					  - A path to an image sampler.
			* - value
			  - Number
			  - The metalness value. Is used if no texture is specified.
			  - Any number.
	* - roughness
	  - Object
	  - The roughness parameter.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - texture
			  - Object
			  - The image and image sampler to use.
			  - .. list-table::
					:width: 100%
					:header-rows: 1
					:class: code-table

					* - Name
					  - Type
					  - Description
					  - Possible values
					* - imagePath
					  - String
					  - The path to the roughness texture.
					  - A path to an image.
					* - imageSamplerPath
					  - String
					  - The path to the :doc:`/file_formats/ntsp/index`.
					  - A path to an image sampler.
			* - value
			  - Number
			  - The roughness value. Is used if no texture is specified.
			  - Any number.
	* - occlusion
	  - Object
	  - The occlusion parameter.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - texture
			  - Object
			  - The image and image sampler to use.
			  - .. list-table::
					:width: 100%
					:header-rows: 1
					:class: code-table

					* - Name
					  - Type
					  - Description
					  - Possible values
					* - imagePath
					  - String
					  - The path to the occlusion texture.
					  - A path to an image.
					* - imageSamplerPath
					  - String
					  - The path to the :doc:`/file_formats/ntsp/index`.
					  - A path to an image sampler.
			* - value
			  - Number
			  - The occlusion value. Is used if no texture is specified.
			  - Any number.
	* - emissive
	  - Object
	  - The emissive parameter.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - texture
			  - Object
			  - The image and image sampler to use.
			  - .. list-table::
					:width: 100%
					:header-rows: 1
					:class: code-table

					* - Name
					  - Type
					  - Description
					  - Possible values
					* - imagePath
					  - String
					  - The path to the emissive texture.
					  - A path to an image.
					* - imageSamplerPath
					  - String
					  - The path to the :doc:`/file_formats/ntsp/index`.
					  - A path to an image sampler.
			* - color
			  - Array of Number
			  - The emissive color.
			  - Any array of 3 numbers, between 0.0 and 1.0. Is used if no texture is specified.
			* - factor
			  - Number
			  - The emissive factor, used to be multiplied with the emissive texture or emissive color.
			  - Any number.
	* - alphaCutoff
	  - Number
	  - The alpha cutoff, used to be compared against the diffuse texture.
	  - Any number between 0.0 and 1.0.
	* - indexOfRefraction
	  - Number
	  - The index of refraction, used to calculate refraction of a transparent object.
	  - Any number.
