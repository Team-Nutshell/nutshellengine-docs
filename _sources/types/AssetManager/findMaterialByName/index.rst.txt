findMaterialByName
==================

:doc:`/types/AssetManager/index`::findMaterialByName

Returns the material associated with the name.

Declaration
-----------

.. code-block:: cpp

	Material* findMaterialByName(const std::string& materialName);

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
	  - The name of the :doc:`/types/Material/index`.

Returns
-------

A pointer to a :doc:`/types/Material/index` if the name is associated with a material, else, returns ``nullptr``.