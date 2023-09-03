Light
=====

.. code-block:: cpp

	struct Light {
		LightType type = LightType::Unknown;
		Math::vec3 color = { 0.0f, 0.0f, 0.0f };
		Math::vec2 cutoff = { 0.0f, 0.0f };
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
	* - type
	  - :doc:`/types/light_type/index`
	  - The light's type.
	* - color
	  - Math::vec3
	  - The light's color.
	* - cutoff
	  - Math::vec2
	  - Only used in spot lights. In radians.
