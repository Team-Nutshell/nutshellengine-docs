ParticleEmitter
===============

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - number
	  - uint32_t
	  - The number of particles per emission.
	* - durationRange
	  - `std::array <https://en.cppreference.com/w/cpp/container/array>`_\<float, 2>
	  - The range of duration per particle, in **seconds**.
	* - positionRange
	  - `std::array <https://en.cppreference.com/w/cpp/container/array>`_\<:doc:`/types/Math/index`::vec3, 2>
	  - The range of position per particle.
	* - baseDirection
	  - :doc:`/types/Math/index`::vec3
	  - The base direction.
	* - rotationRange
	  - `std::array <https://en.cppreference.com/w/cpp/container/array>`_\<:doc:`/types/Math/index`::vec3, 2>
	  - The range of rotation, from the base direction, per particle.
	* - speedRange
	  - `std::array <https://en.cppreference.com/w/cpp/container/array>`_\<float, 2>
	  - The range of speed, per particle.
	* - colorRange
	  - `std::array <https://en.cppreference.com/w/cpp/container/array>`_\<:doc:`/types/Math/index`::vec4, 2>
	  - The range of color per particle.
	* - sizeRange
	  - `std::array <https://en.cppreference.com/w/cpp/container/array>`_\<float, 2>
	  - The range of size, per particle.