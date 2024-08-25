loadMaterial
============

:doc:`/types/Script/index`::loadMaterial

Loads a material from a file in the :doc:`/asset_manager/index` and returns a pointer to the loaded material.

Declaration
-----------

.. code-block:: cpp

	Material* loadMaterial(const std::string& filePath);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - filePath
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - Path to the file to load.

Returns
-------

A pointer to a :doc:`/types/Material/index` containing information about the loaded material.

If the material could not be loaded (for example: if the file does not exist, or the :doc:`/asset_manager/index` or :doc:`/module/asset_loader_module/index` does not support this material file format), the returned pointer is **nullptr**.