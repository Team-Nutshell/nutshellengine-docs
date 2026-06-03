createAnimation
===============

:doc:`/types/Script/index`::createAnimation

Creates an empty animation and returns its pointer.

Declaration
-----------

.. code-block:: cpp

	Animation* createAnimation(const std::string& animationName);

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
	  - A unique name for the new :doc:`/types/Animation/index`.

Returns
-------

A pointer to an empty :doc:`/types/Animation/index`.