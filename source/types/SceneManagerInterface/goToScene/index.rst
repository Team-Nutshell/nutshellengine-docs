goToScene
=========

:doc:`/types/SceneManagerInterface/index`::goToScene

Loads a scene from a file.

Declaration
-----------

.. code-block:: cpp

	virtual void goToScene(const std::string& filePath) = 0;

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
	  - Path to the scene to load.

Returns
-------

None.

Notes
-----

Changing scene will destroy all non-persistent Entities, potentially including the Entity calling this function.

If this is the case, the rest of the script must not reference any function or variable belonging to this Entity. It is safer to return right after calling this function:

.. code-block:: cpp

	sceneManager->goToScene("assets/scenes/scene.ntsn");
	return;
