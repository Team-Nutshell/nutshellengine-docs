Scripting API
=============

The Scripting API is a set of functions that can be used in a **Script**.

Resources
---------

Functions related to the loading of resources.

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Function name
	  - Description
	* - :doc:`/scripting/api/resources/loadModel/index`
	  - Loads a model from a file in the AssetManager and returns a pointer to the loaded model.
	* - :doc:`/scripting/api/resources/getMeshID/index`
	  - Loads a model in the Graphics Module and returns a unique identifier to this model.
	* - :doc:`/scripting/api/resources/loadImage/index`
	  - Loads an image from a file in the AssetManager and returns a pointer to the loaded image.
	* - :doc:`/scripting/api/resources/getImageID/index`
	  - Loads an image in the Graphics Module and returns a unique identifier to this image.
	* - :doc:`/scripting/api/resources/loadFont/index`
	  - Loads a font from a file in the AssetManager and returns a pointer to the loaded font.
	* - :doc:`/scripting/api/resources/getFontID/index`
	  - Loads a font in the Graphics Module and returns a unique identifier to this font.
	* - :doc:`/scripting/api/resources/loadSound/index`
	  - Loads a sound from a file in the AssetManager and returns a pointer to the loaded sound.
	* - :doc:`/scripting/api/resources/getSoundID/index`
	  - Loads a sound in the Audio Module and returns a unique identifier to this sound.

.. toctree::
	:hidden:

	./resources/loadModel/index.rst
	./resources/getMeshID/index.rst
	./resources/loadImage/index.rst
	./resources/getImageID/index.rst
	./resources/loadFont/index.rst
	./resources/getFontID/index.rst
	./resources/loadSound/index.rst
	./resources/getSoundID/index.rst

Scenes
------

Functions related to the scenes.

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Function name
	  - Description
	* - :doc:`/scripting/api/scenes/goToScene/index`
	  - Loads a scene from a file in the SceneManager.
	* - :doc:`/scripting/api/scenes/getCurrentScenePath/index`
	  - Returns the current scene's path.

.. toctree::
	:hidden:

	./scenes/goToScene/index.rst
	./scenes/getCurrentScenePath/index.rst

Entity-Component-System
-----------------------

Functions related to the Entity-Component-System.

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Function name
	  - Description
	* - :doc:`/scripting/api/ecs/createEntity/index`
	  - Creates a new :doc:`/ecs/entity/index`.
	* - :doc:`/scripting/api/ecs/destroyEntity/index`
	  - Destroys an :doc:`/ecs/entity/index`.
	* - :doc:`/scripting/api/ecs/destroyAllEntities/index`
	  - Destroys all Entities.
	* - :doc:`/scripting/api/ecs/destroyNonPersistentEntities/index`
	  - Destroys all Entities not marked as persistent.
	* - :doc:`/scripting/api/ecs/entityExists/index`
	  - Checks if an :doc:`/ecs/entity/index` exists.
	* - :doc:`/scripting/api/ecs/setEntityName/index`
	  - Sets a name to an :doc:`/ecs/entity/index`.
	* - :doc:`/scripting/api/ecs/entityHasName/index`
	  - Checks if an :doc:`/ecs/entity/index` has a name.
	* - :doc:`/scripting/api/ecs/getEntityName/index`
	  - Returns the name of the :doc:`/ecs/entity/index`.
	* - :doc:`/scripting/api/ecs/findEntityByName/index`
	  - Returns the :doc:`/ecs/entity/index` associated with the name.
	* - :doc:`/scripting/api/ecs/setEntityPersistence/index`
	  - Marks or unmarks the :doc:`/ecs/entity/index` as persistent.
	* - :doc:`/scripting/api/ecs/isEntityPersistent/index`
	  - Checks if an :doc:`/ecs/entity/index` is persistent.
	* - :doc:`/scripting/api/ecs/addEntityComponent/index`
	  - Adds a :doc:`/ecs/component/index` to an :doc:`/ecs/entity/index`.
	* - :doc:`/scripting/api/ecs/removeEntityComponent/index`
	  - Removes a :doc:`/ecs/component/index` from an :doc:`/ecs/entity/index`.
	* - :doc:`/scripting/api/ecs/hasEntityComponent/index`
	  - Checks if an :doc:`/ecs/entity/index` has a certain :doc:`/ecs/component/index`.
	* - :doc:`/scripting/api/ecs/getEntityComponent/index`
	  - Returns an :doc:`/ecs/entity/index`'s :doc:`/ecs/component/index`.

.. toctree::
	:hidden:

	./ecs/createEntity/index.rst
	./ecs/destroyEntity/index.rst
	./ecs/destroyAllEntities/index.rst
	./ecs/destroyNonPersistentEntities/index.rst
	./ecs/setEntityName/index.rst
	./ecs/entityHasName/index.rst
	./ecs/getEntityName/index.rst
	./ecs/findEntityByName/index.rst
	./ecs/setEntityPersistence/index.rst
	./ecs/isEntityPersistent/index.rst
	./ecs/addEntityComponent/index.rst
	./ecs/removeEntityComponent/index.rst
	./ecs/hasEntityComponent/index.rst
	./ecs/getEntityComponent/index.rst