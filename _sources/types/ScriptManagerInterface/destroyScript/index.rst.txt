destroyScript
=============

:doc:`/types/ScriptManagerInterface/index`::destroyScript

Destroys a :doc:`/types/Script/index`.

Declaration
-----------

.. code-block:: cpp

	void destroyScript(ScriptBase* script);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - script
	  - :doc:`/types/ScriptBase/index`\*
	  - The :doc:`/types/Script/index` to destroy.

Returns
-------

None.

Notes
-----

This function is called automatically when a :doc:`/types/Scriptable/index` :doc:`/entity_component_system/component/index`, containing a valid script, attached to an :doc:`/entity_component_system/entity/index` is removed.