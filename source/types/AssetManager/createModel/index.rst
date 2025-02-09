createModel
===========

:doc:`/types/AssetManager/index`::createModel

Creates an empty model and returns its pointer.

Declaration
-----------

.. code-block:: cpp

	Model* createModel(const std::string& modelName);

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
	  - A unique name for the new :doc:`/types/Model/index`.

Returns
-------

A pointer to an empty :doc:`/types/Model/index`.