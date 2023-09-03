loadModel
=========

Script::loadModel

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

A pointer to a :doc:`/types/model/index` containing information about the loaded model.

If the model could not be loaded (for example: if the file does not exist, or the Asset Manager or Asset Loader Module does not support this model file format), the returned pointer is **nullptr**.