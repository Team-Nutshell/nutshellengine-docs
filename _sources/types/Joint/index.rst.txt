Joint
=====

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - inverseBindMatrix
	  - :doc:`/types/Math/index`::mat4
	  - The joint's inverse bind matrix. The inverse of the base pose.
	* - localTransform
	  - :doc:`/types/Math/index`::mat4
	  - The joint's local transform.
	* - children
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<uint32_t>
	  - The joint's children, indexed in the :doc:`/types/Mesh/index`'s ``joints`` list.