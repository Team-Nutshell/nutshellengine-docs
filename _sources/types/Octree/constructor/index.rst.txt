Octree
======

:doc:`/types/Octree/index`::Octree

Constructs an Octree.

Declaration
-----------

.. code-block:: cpp

	Octree(const Math::vec3& position, const Math::vec3& size, uint32_t maxDepth);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - position
	  - :doc:`/types/Math/index`::vec3
	  - The :doc:`/types/Octree/index`'s center.
	* - size
	  - :doc:`/types/Math/index`::vec3
	  - Half the size of the :doc:`/types/Octree/index`, on each axis (x, y and z).
	* - maxDepth
	  - uint32_t
	  - The :doc:`/types/Octree/index`'s max depth.

Returns
-------

An empty :doc:`/types/Octree/index` centered on ``position`` and with a size equals to the half of ``size`` on each axis (x, y and z).