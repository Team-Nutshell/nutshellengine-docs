loadModel
=========

:doc:`/types/AssetLoaderModuleInterface/index`::loadModel

Loads a model from a file.

Declaration
-----------

.. code-block:: cpp

	virtual Model loadModel(const std::string& filePath) = 0;

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

A :doc:`/types/Model/index` containing information about the loaded model.

If the model could not be loaded (for example: if the file does not exist, or the Asset Loader Module does not support this model file format), the returned :doc:`/types/Model/index` contains the structure's default information.