loadMaterial
============

:doc:`/types/AssetLoaderModuleInterface/index`::loadMaterial

Loads a material from a file.

Declaration
-----------

.. code-block:: cpp

	virtual Model loadMaterial(const std::string& filePath) = 0;

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

A :doc:`/types/Material/index` containing information about the loaded material.

If the material could not be loaded (for example: if the file does not exist, or the :doc:`/module/asset_loader_module/index` does not support this material file format), the returned :doc:`/types/Material/index` contains the structure's default information.