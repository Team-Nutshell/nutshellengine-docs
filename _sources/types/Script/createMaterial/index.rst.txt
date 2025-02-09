createMaterial
==============

:doc:`/types/Script/index`::createMaterial

Creates an empty material and returns its pointer.

Declaration
-----------

.. code-block:: cpp

	Material* createMaterial(const std::string& materialName);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - materialName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - A unique name for the new :doc:`/types/Material/index`.

Returns
-------

A pointer to an empty :doc:`/types/Material/index`.