Animation
=========

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - duration
	  - float
	  - The animation's complement duration, in **seconds**.
	* - jointChannels
	  - `std::unordered_map <https://en.cppreference.com/w/cpp/container/unordered_map>`_\<uint32_t, :doc:`/types/AnimationChannel/index`>
	  - A map linking a joint index, indexed in the :doc:`/types/Mesh/index`'s ``joints`` list, to all the channels animating this joint.