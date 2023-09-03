Mesh
====

Declaration
-----------

.. code-block:: cpp

	struct Mesh {
		std::vector<Vertex> vertices;
		std::vector<uint32_t> indices;
		MeshTopology topology = MeshTopology::Unknown;
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
	* - vertices
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<:doc:`/types/vertex/index`>
	  - The mesh's vertices.
	* - indices
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<uint32_t>
	  - The mesh's indices.
	* - topology
	  - :doc:`/types/mesh_topology/index`
	  - The mesh's topology.