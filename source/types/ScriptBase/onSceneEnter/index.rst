onSceneEnter
============

:doc:`/types/ScriptBase/index`::onSceneEnter

Is executed after a new scene is loaded.

Declaration
-----------

.. code-block:: cpp

	virtual void onSceneEnter(const std::string& scenePath);

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
	  - The path of the new scene.

Returns
-------

None.

Notes
-----

This function is called after all the :doc:`Entities </entity_component_system/entity/index>` of the new scene are created.

This function is generally only useful on persistent :doc:`Entities </entity_component_system/entity/index>`.