Fragment Shader
===============

The :doc:`/types/Renderable/index` :doc:`/entity_component_system/component/index` accepts custom fragment shaders.

These fragment shaders are written in GLSL and have some special variables.

Inputs
------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - NtshEngn_position
	  - vec3
	  - The fragment's position, in **world-space**.
	* - NtshEngn_normal
	  - vec3
	  - The fragment's normal.
	* - NtshEngn_tangent
	  - vec3
	  - The fragment's tangent.
	* - NtshEngn_bitangent
	  - vec3
	  - The fragment's bitangent.
	* - NtshEngn_uv
	  - vec2
	  - The fragment's texture coordinates.
	* - NtshEngn_color
	  - vec3
	  - The fragment's color from vertex colors.
	* - NtshEngn_tbn
	  - mat3
	  - The fragment's Tangent-Bitangent-Normal matrix.
	* - NtshEngn_diffuseTexture
	  - sampler2D
	  - The object's material's diffuse texture.
	* - NtshEngn_normalTexture
	  - sampler2D
	  - The object's material's normal texture.
	* - NtshEngn_metalnessTexture
	  - sampler2D
	  - The object's material's metalness texture.
	* - NtshEngn_roughnessTexture
	  - sampler2D
	  - The object's material's roughness texture.
	* - NtshEngn_occlusionTexture
	  - sampler2D
	  - The object's material's occlusion texture.
	* - NtshEngn_emissiveTexture
	  - sampler2D
	  - The object's material's emissive texture.
	* - NtshEngn_emissiveFactor
	  - float
	  - The object's material's metalness factor.
	* - NtshEngn_alphaCutoff
	  - float
	  - The object's material's alpha cutoff.
	* - NtshEngn_scaleUV
	  - vec2
	  - The object's material's UV scale.
	* - NtshEngn_offsetUV
	  - vec2
	  - The object's material's UV offset.
	* - NtshEngn_useTriplanarMapping
	  - bool
	  - ``true`` if the object's material uses triplanar mapping, else, ``false``.
	* - NtshEngn_directionalLightCount
	  - uint
	  - The number of directional lights in the scene.
	* - NtshEngn_directionalLight(uint i)
	  - :doc:`/types/Light/index`
	  - The ``i``th directional light.
	* - NtshEngn_directionalLightShadows(uint i, vec p)
	  - float
	  - A value between 0.0 and 1.0 determining how much the position ``p`` is in the shadows of the ``i``th directional light. 0.0 means completely in shadows, 1.0 means not in shadows.
	* - NtshEngn_pointLightCount
	  - uint
	  - The number of point lights in the scene.
	* - NtshEngn_pointLight(uint i)
	  - :doc:`/types/Light/index`
	  - The ``i``th point light.
	* - NtshEngn_pointLightShadows(uint i, vec p)
	  - float
	  - A value between 0.0 and 1.0 determining how much the position ``p`` is in the shadows of the ``i``th point light. 0.0 means completely in shadows, 1.0 means not in shadows.
	* - NtshEngn_spotLightCount
	  - uint
	  - The number of spot lights in the scene.
	* - NtshEngn_spotLight(uint i)
	  - :doc:`/types/Light/index`
	  - The *i*th spot light.
	* - NtshEngn_spotLightShadows(uint i, vec p)
	  - float
	  - A value between 0.0 and 1.0 determining how much the position ``p`` is in the shadows of the ``i``th spot light. 0.0 means completely in shadows, 1.0 means not in shadows.
	* - NtshEngn_ambientLightCount
	  - uint
	  - The number of ambient lights in the scene.
	* - NtshEngn_ambientLight(i)
	  - :doc:`/types/Light/index`
	  - The *i*th ambient light.
	* - NtshEngn_time
	  - float
	  - The time since the application's launch, in **seconds**.
	* - NtshEngn_cameraPosition
	  - vec3
	  - The camera's position, in **world-space**.
	* - NtshEngn_useReversedDepth
	  - bool
	  - ``true`` if the graphics module uses reversed depth (*1* is close, *0* is far), else, ``false`` (*0* is close, *1* is far).

Outputs
-------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - NtshEngn_outColor
	  - vec4
	  - The output color.
	* - NtshEngn_outDepth
	  - float
	  - The output depth.
