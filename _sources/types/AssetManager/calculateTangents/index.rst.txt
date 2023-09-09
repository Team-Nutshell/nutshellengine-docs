calculateTangents
=================

:doc:`/types/AssetManager/index`::calculateTangents

Calculate a :doc:`/types/Mesh/index`'s tangents.

Declaration
-----------

.. code-block:: cpp

	void calculateTangents(Mesh& mesh);

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

If no :doc:`/module/asset_loader_module/index` is used, the :doc:`/types/Mesh/index`'s tangents will not change.