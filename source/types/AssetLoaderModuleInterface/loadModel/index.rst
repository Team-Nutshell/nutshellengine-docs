loadModel
=========

:doc:`/types/AssetLoaderModuleInterface/index`::loadModel

Loads a model from a file.

Declaration
-----------

.. code-block:: cpp

	virtual bool loadModel(const std::string& filePath, Model& model) = 0;

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
	* - model
	  - :doc:`/types/Model/index`&
	  - The model to put the information in.

Returns
-------

``true`` if the model has been successfully loaded, else, if the model could not be loaded (for example: if the file does not exist, or the :doc:`/asset_manager/index` or :doc:`/module/asset_loader_module/index` does not support this model file format (including the case where there is no :doc:`/module/asset_loader_module/index`)), returns ``false``.