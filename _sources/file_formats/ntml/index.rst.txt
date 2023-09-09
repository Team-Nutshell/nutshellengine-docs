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
	* - diffuseTexture
	  - Object
	  - The diffuse texture.
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
	* - normalTexture
	  - Object
	  - The normal texture.
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
	* - metalnessTexture
	  - Object
	  - The metalness texture.
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
	* - roughnessTexture
	  - Object
	  - The roughness texture.
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
	* - occlusionTexture
	  - Object
	  - The occlusion texture.
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
	* - emissiveTexture
	  - Object
	  - The emissive texture.
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
	* - emissiveFactor
	  - Number
	  - The emissive factor, used to be multiplied with the emissive texture.
	  - Any number.
	* - alphaCutoff
	  - Number
	  - The alpha cutoff, used to be compared against the diffuse texture.
	  - Any number between 0.0 and 1.0.
	* - indexOfRefraction
	  - Number
	  - The index of refraction, used to calculate refraction of a transparent object.
	  - Any number.
