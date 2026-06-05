createEntitiesFromScene
=======================

:doc:`/types/SceneManagerInterface/index`::createEntitiesFromScene

Creates Entities from a scene file.

Declaration
-----------

.. code-block:: cpp

	virtual void createEntitiesFromScene(const std::string& filePath) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - filePath
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - Path to the scene to create the Entities from.

Returns
-------

None.

Notes
-----

Contrary to :doc:`/types/SceneManagerInterface/goToScene/index`, this function does not destroy all non-persistent Entities currently present.