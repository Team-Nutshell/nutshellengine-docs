findModelByName
===============

:doc:`/types/AssetManagerInterface/index`::findModelByName

Returns the model associated with the name.

Declaration
-----------

.. code-block:: cpp

	virtual Model* findModelByName(const std::string& modelName) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - modelName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The name of the :doc:`/types/Model/index`.

Returns
-------

A pointer to a :doc:`/types/Model/index` if the name is associated with a model, else, returns ``nullptr``.