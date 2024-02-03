Mesh
====

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - vertices
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<:doc:`/types/Vertex/index`>
	  - The mesh's vertices.
	* - indices
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<uint32_t>
	  - The mesh's indices.
	* - skin
	  - :doc:`/types/Skin/index`
	  - The mesh's :doc:`/types/Skin/index` for animation.
	* - animations
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<:doc:`/types/Animation/index`>
	  - The mesh's animations.
	* - topology
	  - :doc:`/types/MeshTopology/index`
	  - The mesh's topology.