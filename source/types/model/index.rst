Model
=====

Declaration
-----------

.. code-block:: cpp

	struct Model {
		std::vector<ModelPrimitive> primitives;
	};

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - primitives
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<:doc:`/types/model_primitive/index`>
	  - The model's primitives.