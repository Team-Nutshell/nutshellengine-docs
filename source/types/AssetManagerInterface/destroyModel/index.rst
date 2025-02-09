destroyModel
============

:doc:`/types/AssetManagerInterface/index`::destroyModel

Destroys a model.

Declaration
-----------

.. code-block:: cpp

	virtual void destroyModel(const std::string& modelName) = 0;

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
	  - The name of the :doc:`/types/Model/index` to destroy.

Returns
-------

None.