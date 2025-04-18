Material
========

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
	  - :doc:`/types/Texture/index`
	  - The diffuse texture.
	* - normalTexture
	  - :doc:`/types/Texture/index`
	  - The normal texture.
	* - metalnessTexture
	  - :doc:`/types/Texture/index`
	  - The metalness texture.
	* - roughnessTexture
	  - :doc:`/types/Texture/index`
	  - The roughness texture.
	* - occlusionTexture
	  - :doc:`/types/Texture/index`
	  - The occlusion texture.
	* - emissiveTexture
	  - :doc:`/types/Texture/index`
	  - The emissive texture.
	* - emissiveFactor
	  - float
	  - The emissive factor to multiply the emissive texture with.
	* - alphaCutoff
	  - float
	  - The alpha cutoff value to compare with the diffuse texture's alpha channel.
	* - indexOfRefraction
	  - float
	  - The index of refraction.
	* - useTriplanarMapping
	  - bool
	  - If ``true``, the :doc:`/types/Mesh/index`'s ``uv`` are ignored and the world position is used as texture coordinates.
	* - scaleUV
	  - :doc:`/types/Math/index`::vec2
	  - The texture coordinates' scale.
	* - offsetUV
	  - :doc:`/types/Math/index`::vec2
	  - The texture coordinates' offset.