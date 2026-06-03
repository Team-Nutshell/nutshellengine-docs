getAnimationName
================

:doc:`/types/Script/index`::getAnimationName

Returns the name of the animation.

Declaration
-----------

.. code-block:: cpp

	std::string getAnimationName(const Animation* animation);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - animation
	  - const :doc:`/types/Animation/index`\*
	  - The :doc:`/types/Animation/index` to get the name of.

Returns
-------

The name of the :doc:`/types/Animation/index` if it exists, else, returns the empty string ``""``.