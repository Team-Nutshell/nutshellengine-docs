getAnimationName
================

:doc:`/types/AssetManagerInterface/index`::getAnimationName

Returns the name of the animation.

Declaration
-----------

.. code-block:: cpp

	virtual std::string getAnimationName(const Animation* animation) = 0;

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