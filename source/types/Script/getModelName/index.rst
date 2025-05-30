getModelName
============

:doc:`/types/Script/index`::getModelName

Returns the name of the model.

Declaration
-----------

.. code-block:: cpp

	std::string getModelName(const Model* model);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - model
	  - const :doc:`/types/Model/index`\*
	  - The :doc:`/types/Model/index` to get the name of.

Returns
-------

The name of the :doc:`/types/Model/index` if it exists, else, returns the empty string ``""``.