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

	* - Name
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

	* - Name
	  - Description
	* - :doc:`/scripting/script/goToScene/index`
	  - Loads a scene from a file.
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

	* - Name
	  - Description
	* - :doc:`/scripting/script/createEntity/index`
	  - Creates a new :doc:`/entity_component_system/entity/index`.
	* - :doc:`/scripting/script/destroyEntity/index`
	  - Destroys an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/scripting/script/destroyAllEntities/index`
	  - Destroys all Entities.
	* - :doc:`/scripting/script/destroyNonPersistentEntities/index`
	  - Destroys all Entities not marked as persistent.
	* - :doc:`/scripting/script/entityExists/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` exists.
	* - :doc:`/scripting/script/setEntityName/index`
	  - Sets a name to an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/scripting/script/entityHasName/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` has a name.
	* - :doc:`/scripting/script/getEntityName/index`
	  - Returns the name of the :doc:`/entity_component_system/entity/index`.
	* - :doc:`/scripting/script/findEntityByName/index`
	  - Returns the :doc:`/entity_component_system/entity/index` associated with the name.
	* - :doc:`/scripting/script/setEntityPersistence/index`
	  - Marks or unmarks the :doc:`/entity_component_system/entity/index` as persistent.
	* - :doc:`/scripting/script/isEntityPersistent/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` is persistent.
	* - :doc:`/scripting/script/addEntityComponent/index`
	  - Adds a :doc:`/entity_component_system/component/index` to an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/scripting/script/removeEntityComponent/index`
	  - Removes a :doc:`/entity_component_system/component/index` from an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/scripting/script/hasEntityComponent/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` has a certain :doc:`/entity_component_system/component/index`.
	* - :doc:`/scripting/script/getEntityComponent/index`
	  - Returns an :doc:`/entity_component_system/entity/index`'s :doc:`/entity_component_system/component/index`.

Input
-----

Functions related to inputs.

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
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
	  - Checks if the cursor is visible.
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

Windows
-------

Functions related to windows and monitors.

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/scripting/script/openWindow/index`
	  - Opens a new window.
	* - :doc:`/scripting/script/isWindowOpen/index`
	  - Checks if the window is opened.
	* - :doc:`/scripting/script/closeWindow/index`
	  - Closes the window. Closing the main window closes the application.
	* - :doc:`/scripting/script/getMainWindowID/index`
	  - Returns the unique identifier of the main window.
	* - :doc:`/scripting/script/windowCount/index`
	  - Returns the number of opened windows.
	* - :doc:`/scripting/script/setWindowSize/index`
	  - Sets the size of the window.
	* - :doc:`/scripting/script/getWindowWidth/index`
	  - Returns the width of the window.
	* - :doc:`/scripting/script/getWindowHeight/index`
	  - Returns the height of the window.
	* - :doc:`/scripting/script/setWindowPosition/index`
	  - Sets the position of the window on the screen.
	* - :doc:`/scripting/script/getWindowPositionX/index`
	  - Returns the horizontal position of the window on the screen.
	* - :doc:`/scripting/script/getWindowPositionY/index`
	  - Returns the vertical position of the window on the screen.
	* - :doc:`/scripting/script/setWindowFullscreen/index`
	  - Puts the window in fullscreen or windowed.
	* - :doc:`/scripting/script/isWindowFullscreen/index`
	  - Checks if the window is in fullscreen.
	* - :doc:`/scripting/script/setWindowBorderless/index`
	  - Removes or adds the window decorations.
	* - :doc:`/scripting/script/isWindowBorderless/index`
	  - Checks if the window decorations are shown.
	* - :doc:`/scripting/script/setWindowResizable/index`
	  - Enables or disables manual window resizing.
	* - :doc:`/scripting/script/isWindowResizable/index`
	  - Checks if the window can be manually resized.
	* - :doc:`/scripting/script/setWindowTitle/index`
	  - Sets the window's title.
	* - :doc:`/scripting/script/setWindowIcon/index`
	  - Sets the window's icon.
	* - :doc:`/scripting/script/getMonitorWidth/index`
	  - Returns the width of the main monitor.
	* - :doc:`/scripting/script/getMonitorHeight/index`
	  - Returns the height of the main monitor.
	* - :doc:`/scripting/script/getMonitorRefreshRate/index`
	  - Returns the refresh rate of the main monitor.
	* - :doc:`/scripting/script/getMonitorDisplayScaling/index`
	  - Returns the display scaling of the main monitor.

Physics
-------

Functions related to physics.

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/scripting/script/intersect/index`
	  - Returns information about the intersection of two :doc:`/types/ColliderShape/index`\s.
	* - :doc:`/scripting/script/raycast/index`
	  - Casts a ray and returns information about the hit Entities.

Audio
-----

Functions related to audio.

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/scripting/script/playSound/index`
	  - Plays or resumes a sound.
	* - :doc:`/scripting/script/pauseSound/index`
	  - Pauses a sound.
	* - :doc:`/scripting/script/stopSound/index`
	  - Stops a sound.
	* - :doc:`/scripting/script/isSoundPlaying/index`
	  - Checks if a sound is currently playing.
	* - :doc:`/scripting/script/setSoundGain/index`
	  - Sets the gain of a sound.
	* - :doc:`/scripting/script/getSoundGain/index`
	  - Returns the gain of a sound.
	* - :doc:`/scripting/script/setSoundPitch/index`
	  - Sets the pitch of a sound.
	* - :doc:`/scripting/script/getSoundPitch/index`
	  - Returns the pitch of a sound.

User Interface
--------------

Functions related to the User Interface.

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/scripting/script/drawUIText/index`
	  - Draws text on the User Interface.
	* - :doc:`/scripting/script/drawUILine/index`
	  - Draws a line on the User Interface.
	* - :doc:`/scripting/script/drawUIRectangle/index`
	  - Draws a rectangle on the User Interface.
	* - :doc:`/scripting/script/drawUIImage/index`
	  - Draws an image on the User Interface.
	* - :doc:`/scripting/script/drawUIButton/index`
	  - Draws a button on the User Interface and returns an :doc:`/scripting/script/UIElementState/index`.

Frame Limiter
-------------

Functions related to maximum number of frames per second.

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/scripting/script/setMaxFPS/index`
	  - Sets the maximum number of frames per second.
	* - :doc:`/scripting/script/getMaxFPS/index`
	  - Returns the maximum number of frames per second.

Job System
----------

Functions related to multithreading.

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/scripting/script/executeJob/index`
	  - Launches a job to be executed by a worker thread.
	* - :doc:`/scripting/script/dispatchJob/index`
	  - Launches a job to be executed by multiple worker threads.
	* - :doc:`/scripting/script/waitAllThreads/index`
	  - Waits for all worker threads to finish their jobs.
	* - :doc:`/scripting/script/getNumThreads/index`
	  - Returns the number of threads.

Networking
----------

Functions related to networking.

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/scripting/script/createServerSocket/index`
	  - Creates a :doc:`/networking/ServerSocket/index`.
	* - :doc:`/scripting/script/createClientSocket/index`
	  - Creates a :doc:`/networking/ClientSocket/index`.
	* - :doc:`/scripting/script/closeServerSocket/index`
	  - Closes a :doc:`/networking/ServerSocket/index`.
	* - :doc:`/scripting/script/closeClientSocket/index`
	  - Closes a :doc:`/networking/ClientSocket/index`.