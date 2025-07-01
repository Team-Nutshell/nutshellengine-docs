onSceneExit
===========

:doc:`/types/ScriptBase/index`::onSceneExit

Is executed before a new scene is loaded.

Declaration
-----------

.. code-block:: cpp

	virtual void onSceneExit(const std::string& scenePath);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - scenePath
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The path of the previous scene.

Returns
-------

None.

Notes
-----

This function is called before the :doc:`Entities </entity_component_system/entity/index>` of the previous scene are destroyed.

This function is generally only useful on persistent :doc:`Entities </entity_component_system/entity/index>`.