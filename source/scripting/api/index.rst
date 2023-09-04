Scripting API
=============

The Scripting API is a set of functions that can be used in a :doc:`/scripting/script/index`.

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
	* - :doc:`/scripting/script/loadModel/index`
	  - Loads a model from a file in the AssetManager and returns a pointer to the loaded model.
	* - :doc:`/scripting/script/getMeshID/index`
	  - Loads a model in the Graphics Module and returns a unique identifier to this model.
	* - :doc:`/scripting/script/loadImage/index`
	  - Loads an image from a file in the AssetManager and returns a pointer to the loaded image.
	* - :doc:`/scripting/script/getImageID/index`
	  - Loads an image in the Graphics Module and returns a unique identifier to this image.
	* - :doc:`/scripting/script/loadFont/index`
	  - Loads a font from a file in the AssetManager and returns a pointer to the loaded font.
	* - :doc:`/scripting/script/getFontID/index`
	  - Loads a font in the Graphics Module and returns a unique identifier to this font.
	* - :doc:`/scripting/script/loadSound/index`
	  - Loads a sound from a file in the AssetManager and returns a pointer to the loaded sound.
	* - :doc:`/scripting/script/getSoundID/index`
	  - Loads a sound in the Audio Module and returns a unique identifier to this sound.

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
	* - :doc:`/scripting/script/goToScene/index`
	  - Loads a scene from a file in the SceneManager.
	* - :doc:`/scripting/script/getCurrentScenePath/index`
	  - Returns the current scene's path.

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
	* - :doc:`/scripting/script/createEntity/index`
	  - Creates a new :doc:`/ecs/entity/index`.
	* - :doc:`/scripting/script/destroyEntity/index`
	  - Destroys an :doc:`/ecs/entity/index`.
	* - :doc:`/scripting/script/destroyAllEntities/index`
	  - Destroys all Entities.
	* - :doc:`/scripting/script/destroyNonPersistentEntities/index`
	  - Destroys all Entities not marked as persistent.
	* - :doc:`/scripting/script/entityExists/index`
	  - Checks if an :doc:`/ecs/entity/index` exists.
	* - :doc:`/scripting/script/setEntityName/index`
	  - Sets a name to an :doc:`/ecs/entity/index`.
	* - :doc:`/scripting/script/entityHasName/index`
	  - Checks if an :doc:`/ecs/entity/index` has a name.
	* - :doc:`/scripting/script/getEntityName/index`
	  - Returns the name of the :doc:`/ecs/entity/index`.
	* - :doc:`/scripting/script/findEntityByName/index`
	  - Returns the :doc:`/ecs/entity/index` associated with the name.
	* - :doc:`/scripting/script/setEntityPersistence/index`
	  - Marks or unmarks the :doc:`/ecs/entity/index` as persistent.
	* - :doc:`/scripting/script/isEntityPersistent/index`
	  - Checks if an :doc:`/ecs/entity/index` is persistent.
	* - :doc:`/scripting/script/addEntityComponent/index`
	  - Adds a :doc:`/ecs/component/index` to an :doc:`/ecs/entity/index`.
	* - :doc:`/scripting/script/removeEntityComponent/index`
	  - Removes a :doc:`/ecs/component/index` from an :doc:`/ecs/entity/index`.
	* - :doc:`/scripting/script/hasEntityComponent/index`
	  - Checks if an :doc:`/ecs/entity/index` has a certain :doc:`/ecs/component/index`.
	* - :doc:`/scripting/script/getEntityComponent/index`
	  - Returns an :doc:`/ecs/entity/index`'s :doc:`/ecs/component/index`.

Input
-----

Functions related to inputs.

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Function name
	  - Description
	* - :doc:`/scripting/script/getKeyState/index`
	  - Returns the state of a keyboard key.
	* - :doc:`/scripting/script/getMouseButtonState/index`
	  - Returns the state of a mouse button.
	* - :doc:`/scripting/script/setCursorPosition/index`
	  - Sets the mouse cursor position.
	* - :doc:`/scripting/script/getCursorPositionX/index`
	  - Returns the mouse cursor horizontal position.
	* - :doc:`/scripting/script/getCursorPositionY/index`
	  - Returns the mouse cursor vertical position.
	* - :doc:`/scripting/script/getMouseScrollOffsetX/index`
	  - Returns the horizontal mouse scroll offset between the last and current frame.
	* - :doc:`/scripting/script/getMouseScrollOffsetY/index`
	  - Returns the vertical mouse scroll offset between the last and current frame.
	* - :doc:`/scripting/script/setCursorVisibility/index`
	  - Sets the mouse cursor's visibility.
	* - :doc:`/scripting/script/isCursorVisible/index`
	  - Returns true if the mouse cursor is visible, else, returns false.
	* - :doc:`/scripting/script/getConnectedGamepads/index`
	  - Returns the list of connected gamepads.
	* - :doc:`/scripting/script/getGamepadButtonState/index`
	  - Returns the state of the gamepad with identifier gamepadID.
	* - :doc:`/scripting/script/getGamepadStickAxisX/index`
	  - Returns the value of the stick's horizontal axis, with -1.0 being left, 0.0 neutral and 1.0 right.
	* - :doc:`/scripting/script/getGamepadStickAxisY/index`
	  - Returns the value of the stick's vertical axis, with -1.0 being up, 0.0 neutral and 1.0 down.
	* - :doc:`/scripting/script/getGamepadLeftTrigger/index`
	  - Returns the value of the stick's left trigger, with 0.0 being neutral and 1.0 being fully pressed.
	* - :doc:`/scripting/script/getGamepadRightTrigger/index`
	  - Returns the value of the stick's right trigger, with 0.0 being neutral and 1.0 being fully pressed.
	* - :doc:`/scripting/script/getGamepadName/index`
	  - Returns the name of the gamepad.
