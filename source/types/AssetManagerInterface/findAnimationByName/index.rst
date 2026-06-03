findAnimationByName
===================

:doc:`/types/AssetManagerInterface/index`::findAnimationByName

Returns the animation associated with the name.

Declaration
-----------

.. code-block:: cpp

	virtual Animation* findAnimationByName(const std::string& animationName) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - animationName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The name of the :doc:`/types/Animation/index`.

Returns
-------

A pointer to an :doc:`/types/Animation/index` if the name is associated with an Animation, else, returns ``nullptr``.