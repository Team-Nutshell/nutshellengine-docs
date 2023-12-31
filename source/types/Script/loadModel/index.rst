loadModel
=========

:doc:`/types/Script/index`::loadModel

Loads a model from a file in the :doc:`/asset_manager/index` and returns a pointer to the loaded model.

Declaration
-----------

.. code-block:: cpp

	Model* loadModel(const std::string& filePath);

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

A pointer to a :doc:`/types/Model/index` containing information about the loaded model.

If the model could not be loaded (for example: if the file does not exist, or the :doc:`/asset_manager/index` or :doc:`/module/asset_loader_module/index` does not support this model file format), the returned pointer is **nullptr**.