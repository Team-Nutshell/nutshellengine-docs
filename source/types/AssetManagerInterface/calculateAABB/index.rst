calculateAABB
=============

:doc:`/types/AssetManagerInterface/index`::calculateAABB

Calculate a :doc:`/types/Mesh/index`'s AABB.

Declaration
-----------

.. code-block:: cpp

	virtual std::array<Math::vec3, 2> calculateAABB(const Mesh& mesh) = 0;

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
	  - const :doc:`/types/Mesh/index`\&
	  - The mesh to calculate the AABB of.

Returns
-------

An `std::array <https://en.cppreference.com/w/cpp/container/array>`_ of 2 :doc:`/types/Math/index`::vec3. The first one contains the minimum corner and the second one contains the maximum corner.

Notes
-----

If a :doc:`/types/Mesh/index`'s minimum corner's axis (x, y or z) is equal to a maximum corner's axis (which can happen if the mesh is a plane, for example), a small epsilon is deduced from this minimum corner's axis and added to this maximum corner's axis, to avoid the case where the AABB has no volume.