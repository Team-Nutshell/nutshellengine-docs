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
	* - joints
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<:doc:`/types/Joint/index`>
	  - The mesh's joints.
	* - topology
	  - :doc:`/types/MeshTopology/index`
	  - The mesh's topology.