getMaterialName
===============

:doc:`/types/Script/index`::getMaterialName

Returns the name of the material.

Declaration
-----------

.. code-block:: cpp

	std::string getMaterialName(const Material* material);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - material
	  - const :doc:`/types/Material/index`\*
	  - The :doc:`/types/Material/index` to get the name of.

Returns
-------

The name of the :doc:`/types/Material/index` if it exists, else, returns the empty string ``""``.