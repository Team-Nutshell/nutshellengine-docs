Material
========

Declaration
-----------

.. code-block:: cpp

	struct Material {
		Texture diffuseTexture;
		Texture normalTexture;
		Texture metalnessTexture;
		Texture roughnessTexture;
		Texture occlusionTexture;
		Texture emissiveTexture;
		float emissiveFactor = 1.0f;
		float alphaCutoff = 0.0f;
		float indexOfRefraction = 1.0f;
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
	* - diffuseTexture
	  - :doc:`/types/texture/index`
	  - The diffuse texture.
	* - normalTexture
	  - :doc:`/types/texture/index`
	  - The normal texture.
	* - metalnessTexture
	  - :doc:`/types/texture/index`
	  - The metalness texture.
	* - roughnessTexture
	  - :doc:`/types/texture/index`
	  - The roughness texture.
	* - occlusionTexture
	  - :doc:`/types/texture/index`
	  - The occlusion texture.
	* - emissiveTexture
	  - :doc:`/types/texture/index`
	  - The emissive texture.
	* - emissiveFactor
	  - float
	  - The emissive factor to multiply the emissive texture with.
	* - alphaCutoff
	  - float
	  - The alpha cutoff value to compare with the diffuse texture.
	* - indexOfRefraction
	  - float
	  - The index of refraction.