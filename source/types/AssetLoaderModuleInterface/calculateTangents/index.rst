calculateTangents
=================

:doc:`/types/AssetLoaderModuleInterface/index`::calculateTangents

Calculate a :doc:`/types/Mesh/index`'s tangents.

Declaration
-----------

.. code-block:: cpp

	virtual void calculateTangents(Mesh& mesh) = 0;

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
	  - :doc:`/types/Mesh/index`\&
	  - The mesh to calculate the tangents of.

Returns
-------

None.

Notes
-----

The calculated vertex tangents are directly written in ``mesh``'s vertices.

The tangents consist of a 3D direction (x, y and z) and a either 1.0 or -1.0 on w.