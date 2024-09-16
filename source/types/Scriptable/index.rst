Scriptable
==========

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - script
	  - :doc:`/types/ScriptBase/index`\*
	  - The script to use.

Notes
-----

JSON for the :doc:`/file_formats/ntsn/index` scene file format:

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	  - Possible values
	* - scriptable
	  - Array of Object
	  - The :doc:`/types/Scriptable/index` :doc:`/entity_component_system/component/index`.
	  - .. list-table::
			:width: 100%
			:header-rows: 1
			:class: code-table

			* - Name
			  - Type
			  - Description
			  - Possible values
			* - scriptName
			  - String
			  - The name of the :doc:`/types/Script/index`.
			  - Any existing :doc:`/types/Script/index`'s name.
			* - editableVariables
			  - Array of Object
			  - The list of the script's editable variables.
			  - Any editable variables in the script.

When creating a :doc:`/types/Scriptable/index` :doc:`/entity_component_system/component/index` from a :doc:`/types/Script/index`, it is recommended to use the :doc:`/types/Script/index`'s :doc:`/types/Script/createScript/index` function.