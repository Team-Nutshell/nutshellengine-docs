AnimationKeyframe
=================

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - timestamp
	  - float
	  - The keyframe's timestamp, in **seconds**.
	* - value
	  - :doc:`/types/Math/index`::vec4
	  - The keyframe's value. Represents a :doc:`/types/Math/index`::vec3 if the :doc:`/types/AnimationChannel/index`'s :doc:`/types/AnimationChannelTransformType/index` is Translation or Scale. Represents a :doc:`/types/Math/index`::quat if it is Rotation.
