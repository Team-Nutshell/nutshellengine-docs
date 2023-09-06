Octree
======

:doc:`/utils/Octree/index`::Octree

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
	  - :doc:`/utils/Math/index`::vec3
	  - The :doc:`/utils/Octree/index`'s center.
	* - size
	  - :doc:`/utils/Math/index`::vec3
	  - Half the size of the :doc:`/utils/Octree/index`, on each axis (x, y and z).
	* - maxDepth
	  - uint32_t
	  - The :doc:`/utils/Octree/index`'s max depth.

Returns
-------

An empty :doc:`/utils/Octree/index` centered on ``position`` and with a size equals to the half of ``size`` on each axis (x, y and z).