Skin
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
	* - joints
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<:doc:`/types/Joint/index`>
	  - The skin's joints.
	* - rootJoints
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<uint32_t>
	  - The skin's root :doc:`Joints </types/Joint/index>`, starting joint hierarchies and indexed in ``joints``.
	* - baseMatrix
	  - :doc:`/types/Math/index`::mat4
	  - The skin's base matrix used to transform the root joint.
	* - inverseGlobalTransform
	  - :doc:`/types/Math/index`::mat4
	  - The skin's inverse global transform matrix.