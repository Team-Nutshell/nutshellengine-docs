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
	  - `std::unique_ptr <https://en.cppreference.com/w/cpp/memory/unique_ptr>`_\<ScriptBase>
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
	  - The :doc:`/types/Scriptable/index` Component.
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