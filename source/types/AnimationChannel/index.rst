AnimationChannel
================

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - interpolationType
	  - :doc:`/types/AnimationChannelInterpolationType/index`
	  - The channel's interpolation type (Step, Linear or CubicSpline).
	* - transformType
	  - :doc:`/types/AnimationChannelTransformType/index`
	  - The channel's affected transform component (Translation, Rotation or Scale).
	* - keyframes
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<:doc:`/types/AnimationChannelKeyframe/index`>
	  - The channel's keyframes.