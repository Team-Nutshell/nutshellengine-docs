destroyMaterial
===============

:doc:`/types/AssetManagerInterface/index`::destroyMaterial

Destroys a material.

Declaration
-----------

.. code-block:: cpp

	virtual void destroyMaterial(Material* material) = 0;

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
	  - :doc:`/types/Material/index`\*
	  - The memory address of the :doc:`/types/Material/index` to destroy.

Returns
-------

None.