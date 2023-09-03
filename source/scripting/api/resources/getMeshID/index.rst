getMeshID
=========

Script::getMeshID

Declaration
-----------

.. code-block:: cpp

	MeshID getMeshID(const Mesh& mesh);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - mesh
	  - const :doc:`/types/mesh/index`\&
	  - Mesh to load in the Graphics Module.

Returns
-------

A unique :doc:`/types/mesh_id/index` identifier for the mesh.

If the mesh could not be loaded, the returned value is ``NTSHENGN_MESH_UNKNOWN``.