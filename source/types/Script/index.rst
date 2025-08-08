Script
======

*Inherits* :doc:`/types/ScriptBase/index`.

For a version of this page but split by categories, see :doc:`/scripting/api/index`.

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - entityID
	  - :doc:`/entity_component_system/entity/index`
	  - The :doc:`/entity_component_system/entity/index`'s own identifier.
	* - graphicsModule
	  - :doc:`/types/GraphicsModuleInterface/index`\*
	  - Memory address to the :doc:`/module/graphics_module/index`.
	* - physicsModule
	  - :doc:`/types/PhysicsModuleInterface/index`\*
	  - Memory address to the :doc:`/module/physics_module/index`.
	* - windowModule
	  - :doc:`/types/WindowModuleInterface/index`\*
	  - Memory address to the :doc:`/module/window_module/index`.
	* - audioModule
	  - :doc:`/types/AudioModuleInterface/index`\*
	  - Memory address to the :doc:`/module/audio_module/index`.
	* - ecs
	  - :doc:`/types/ECSInterface/index`\*
	  - Memory address to the :doc:`/entity_component_system/index`.
	* - assetManager
	  - :doc:`/types/AssetManagerInterface/index`\*
	  - Memory address to the :doc:`/asset_manager/index`.
	* - frameLimiter
	  - :doc:`/types/FrameLimiterInterface/index`\*
	  - Memory address to the :doc:`/frame_limiter/index`.
	* - jobSystem
	  - :doc:`/types/JobSystemInterface/index`\*
	  - Memory address to the :doc:`/job_system/index`.
	* - networking
	  - :doc:`/types/NetworkingInterface/index`\*
	  - Memory address to the :doc:`/networking/index`.
	* - sceneManager
	  - :doc:`/types/SceneManagerInterface/index`\*
	  - Memory address to the manager of :doc:`Scenes </scene/index>`.

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/Script/init/index`
	  - Initialization function executed once, when the :doc:`/types/Script/index` is created.
	* - :doc:`/types/Script/update/index`
	  - Update function executed once per frame.
	* - :doc:`/types/Script/destroy/index`
	  - Destruction function executed once, when the :doc:`/types/Script/index` is destroyed.
	* - :doc:`/types/Script/createModel/index`
	  - Creates an empty model and returns its pointer.
	* - :doc:`/types/Script/loadModel/index`
	  - Loads a model from a file in the :doc:`/asset_manager/index` and returns a pointer to the loaded model.
	* - :doc:`/types/Script/getMeshID/index`
	  - Loads a mesh in the :doc:`/module/graphics_module/index` and returns a unique identifier to this mesh.
	* - :doc:`/types/Script/destroyModel/index`
	  - Destroys a model.
	* - :doc:`/types/Script/findModelByName/index`
	  - Returns the model associated with the name.
	* - :doc:`/types/Script/getModelName/index`
	  - Returns the name of the model.
	* - :doc:`/types/Script/createMaterial/index`
	  - Creates an empty material and returns its pointer.
	* - :doc:`/types/Script/loadMaterial/index`
	  - Loads a material from a file in the :doc:`/asset_manager/index` and returns a pointer to the loaded material.
	* - :doc:`/types/Script/destroyMaterial/index`
	  - Destroys a material.
	* - :doc:`/types/Script/findMaterialByName/index`
	  - Returns the material associated with the name.
	* - :doc:`/types/Script/getMaterialName/index`
	  - Returns the name of the material.
	* - :doc:`/types/Script/createImage/index`
	  - Creates an empty image and returns its pointer.
	* - :doc:`/types/Script/loadImage/index`
	  - Loads an image from a file in the :doc:`/asset_manager/index` and returns a pointer to the loaded image.
	* - :doc:`/types/Script/getImageID/index`
	  - Loads an image in the :doc:`/module/graphics_module/index` and returns a unique identifier to this image.
	* - :doc:`/types/Script/destroyImage/index`
	  - Destroys an image.
	* - :doc:`/types/Script/findImageByName/index`
	  - Returns the image associated with the name.
	* - :doc:`/types/Script/getImageName/index`
	  - Returns the name of the image.
	* - :doc:`/types/Script/createFont/index`
	  - Creates an empty font and returns its pointer.
	* - :doc:`/types/Script/loadFontBitmap/index`
	  - Loads a bitmap font from a file and returns a pointer to the loaded font.
	* - :doc:`/types/Script/loadFontSDF/index`
	  - Loads a SDF font from a file and returns a pointer to the loaded font.
	* - :doc:`/types/Script/getFontID/index`
	  - Loads a font in the :doc:`/module/graphics_module/index` and returns a unique identifier to this font.
	* - :doc:`/types/Script/destroyFont/index`
	  - Destroys a font.
	* - :doc:`/types/Script/findFontByName/index`
	  - Returns the font associated with the name.
	* - :doc:`/types/Script/getFontName/index`
	  - Returns the name of the font.
	* - :doc:`/types/Script/createSound/index`
	  - Creates an empty sound and returns its pointer.
	* - :doc:`/types/Script/loadSound/index`
	  - Loads a sound from a file in the :doc:`/asset_manager/index` and returns a pointer to the loaded sound.
	* - :doc:`/types/Script/getSoundID/index`
	  - Loads a sound in the :doc:`/module/audio_module/index` and returns a unique identifier to this sound.
	* - :doc:`/types/Script/destroySound/index`
	  - Destroys a sound.
	* - :doc:`/types/Script/findSoundByName/index`
	  - Returns the sound associated with the name.
	* - :doc:`/types/Script/getSoundName/index`
	  - Returns the name of the sound.
	* - :doc:`/types/Script/goToScene/index`
	  - Loads a scene from a file.
	* - :doc:`/types/Script/getCurrentScenePath/index`
	  - Returns the current scene's path.
	* - :doc:`/types/Script/createEntity/index`
	  - Creates a new :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/Script/destroyEntity/index`
	  - Destroys an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/Script/destroyAllEntities/index`
	  - Destroys all :doc:`Entities </entity_component_system/entity/index>`.
	* - :doc:`/types/Script/destroyNonPersistentEntities/index`
	  - Destroys all :doc:`Entities </entity_component_system/entity/index>` not marked as persistent.
	* - :doc:`/types/Script/entityExists/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` exists.
	* - :doc:`/types/Script/getEntities/index`
	  - Returns all the :doc:`Entities </entity_component_system/entity/index>`.
	* - :doc:`/types/Script/setEntityName/index`
	  - Sets a name to an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/Script/entityHasName/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` has a name.
	* - :doc:`/types/Script/getEntityName/index`
	  - Returns the name of the :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/Script/findEntityByName/index`
	  - Returns the :doc:`/entity_component_system/entity/index` associated with the name.
	* - :doc:`/types/Script/setEntityPersistence/index`
	  - Marks or unmarks the :doc:`/entity_component_system/entity/index` as persistent.
	* - :doc:`/types/Script/isEntityPersistent/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` is persistent.
	* - :doc:`/types/Script/addEntityToEntityGroup/index`
	  - Adds an :doc:`/entity_component_system/entity/index` to an Entity Group.
	* - :doc:`/types/Script/removeEntityFromEntityGroup/index`
	  - Removes an :doc:`/entity_component_system/entity/index` from an Entity Group.
	* - :doc:`/types/Script/entityGroupExists/index`
	  - Checks if an Entity Group exists.
	* - :doc:`/types/Script/isEntityInEntityGroup/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` is in an Entity Group.
	* - :doc:`/types/Script/getEntitiesInEntityGroup/index`
	  - Returns the :doc:`Entities </entity_component_system/entity/index>` in an Entity Group.
	* - :doc:`/types/Script/getEntityGroupsOfEntity/index`
	  - Returns the Entity Groups of an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/Script/addEntityComponent/index`
	  - Adds a :doc:`/entity_component_system/component/index` to an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/Script/removeEntityComponent/index`
	  - Removes a :doc:`/entity_component_system/component/index` from an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/Script/hasEntityComponent/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` has a certain :doc:`/entity_component_system/component/index`.
	* - :doc:`/types/Script/getEntityComponent/index`
	  - Returns an :doc:`/entity_component_system/entity/index`'s :doc:`/entity_component_system/component/index`.
	* - :doc:`/types/Script/getKeyState/index`
	  - Returns the state of a keyboard key.
	* - :doc:`/types/Script/getMouseButtonState/index`
	  - Returns the state of a mouse button.
	* - :doc:`/types/Script/setCursorPosition/index`
	  - Sets the mouse cursor position.
	* - :doc:`/types/Script/getCursorPositionX/index`
	  - Returns the mouse cursor horizontal position.
	* - :doc:`/types/Script/getCursorPositionY/index`
	  - Returns the mouse cursor vertical position.
	* - :doc:`/types/Script/getMouseScrollOffsetX/index`
	  - Returns the horizontal mouse scroll offset between the last and current frame.
	* - :doc:`/types/Script/getMouseScrollOffsetY/index`
	  - Returns the vertical mouse scroll offset between the last and current frame.
	* - :doc:`/types/Script/setCursorVisibility/index`
	  - Sets the mouse cursor's visibility.
	* - :doc:`/types/Script/isCursorVisible/index`
	  - Checks if the cursor is visible.
	* - :doc:`/types/Script/getConnectedGamepads/index`
	  - Returns the list of connected gamepads.
	* - :doc:`/types/Script/getGamepadButtonState/index`
	  - Returns the state of a gamepad button.
	* - :doc:`/types/Script/getGamepadStickAxisX/index`
	  - Returns the value of the stick's horizontal axis, with -1.0 being left, 0.0 neutral and 1.0 right.
	* - :doc:`/types/Script/getGamepadStickAxisY/index`
	  - Returns the value of the stick's vertical axis, with -1.0 being up, 0.0 neutral and 1.0 down.
	* - :doc:`/types/Script/getGamepadLeftTrigger/index`
	  - Returns the value of the stick's left trigger, with 0.0 being neutral and 1.0 being fully pressed.
	* - :doc:`/types/Script/getGamepadRightTrigger/index`
	  - Returns the value of the stick's right trigger, with 0.0 being neutral and 1.0 being fully pressed.
	* - :doc:`/types/Script/getGamepadName/index`
	  - Returns the name of the gamepad.
	* - :doc:`/types/Script/openWindow/index`
	  - Opens a new window.
	* - :doc:`/types/Script/isWindowOpen/index`
	  - Checks if the window is opened.
	* - :doc:`/types/Script/closeWindow/index`
	  - Closes the window. Closing the main window closes the application.
	* - :doc:`/types/Script/getMainWindowID/index`
	  - Returns the unique identifier of the main window.
	* - :doc:`/types/Script/windowCount/index`
	  - Returns the number of opened windows.
	* - :doc:`/types/Script/setWindowSize/index`
	  - Sets the size of the window.
	* - :doc:`/types/Script/getWindowWidth/index`
	  - Returns the width of the window.
	* - :doc:`/types/Script/getWindowHeight/index`
	  - Returns the height of the window.
	* - :doc:`/types/Script/setWindowPosition/index`
	  - Sets the position of the window on the screen.
	* - :doc:`/types/Script/getWindowPositionX/index`
	  - Returns the horizontal position of the window on the screen.
	* - :doc:`/types/Script/getWindowPositionY/index`
	  - Returns the vertical position of the window on the screen.
	* - :doc:`/types/Script/setWindowFullscreen/index`
	  - Puts the window in fullscreen or windowed.
	* - :doc:`/types/Script/isWindowFullscreen/index`
	  - Checks if the window is in fullscreen.
	* - :doc:`/types/Script/setWindowBorderless/index`
	  - Removes or adds the window decorations.
	* - :doc:`/types/Script/isWindowBorderless/index`
	  - Checks if the window decorations are shown.
	* - :doc:`/types/Script/setWindowResizable/index`
	  - Enables or disables manual window resizing.
	* - :doc:`/types/Script/isWindowResizable/index`
	  - Checks if the window can be manually resized.
	* - :doc:`/types/Script/setWindowOpacity/index`
	  - Sets the window's opacity.
	* - :doc:`/types/Script/getWindowOpacity/index`
	  - Returns the window's opacity.
	* - :doc:`/types/Script/getWindowDroppedFiles/index`
	  - Returns the path to the files dropped on the window.
	* - :doc:`/types/Script/setWindowFocus/index`
	  - Focuses the window.
	* - :doc:`/types/Script/isWindowFocused/index`
	  - Checks if the window is focused.
	* - :doc:`/types/Script/setWindowTitle/index`
	  - Sets the window's title.
	* - :doc:`/types/Script/getWindowTitle/index`
	  - Returns the window's title.
	* - :doc:`/types/Script/setWindowIcon/index`
	  - Sets the window's icon.
	* - :doc:`/types/Script/getMonitorWidth/index`
	  - Returns the width of the main monitor.
	* - :doc:`/types/Script/getMonitorHeight/index`
	  - Returns the height of the main monitor.
	* - :doc:`/types/Script/getMonitorRefreshRate/index`
	  - Returns the refresh rate of the main monitor.
	* - :doc:`/types/Script/getMonitorDisplayScaling/index`
	  - Returns the display scaling of the main monitor.
	* - :doc:`/types/Script/setBackgroundColor/index`
	  - Sets the color of the background.
	* - :doc:`/types/Script/emitParticles/index`
	  - Emits particles described by a :doc:`/types/ParticleEmitter/index`.
	* - :doc:`/types/Script/destroyParticles/index`
	  - Destroys all particles.
	* - :doc:`/types/Script/intersect/index`
	  - Returns information about the intersection of two :doc:`ColliderShapes </types/ColliderShape/index>`.
	* - :doc:`/types/Script/raycast/index`
	  - Casts a ray and returns information about the intersection between the ray and the :doc:`/types/ColliderShape/index`.
	* - :doc:`/types/Script/raycastAll/index`
	  - Casts a ray and returns information about the hit :doc:`Entities </entity_component_system/entity/index>`.
	* - :doc:`/types/Script/setConstantForces/index`
	  - Sets the constant forces.
	* - :doc:`/types/Script/getConstantForces/index`
	  - Returns the constant forces.
	* - :doc:`/types/Script/playSound/index`
	  - Plays a global sound and returns a unique identifier to this sound source.
	* - :doc:`/types/Script/playSoundAtPosition/index`
	  - Plays a sound at a certain position and returns a unique identifier to this sound source.
	* - :doc:`/types/Script/resumeSoundSource/index`
	  - Resumes a paused sound source.
	* - :doc:`/types/Script/pauseSoundSource/index`
	  - Pauses a playing sound source.
	* - :doc:`/types/Script/stopSoundSource/index`
	  - Stops a playing or paused sound.
	* - :doc:`/types/Script/getSoundSourceState/index`
	  - Returns the state of a sound source.
	* - :doc:`/types/Script/isSoundPlaying/index`
	  - Checks if any sound source of a certain sound is playing.
	* - :doc:`/types/Script/setSoundSourcePosition/index`
	  - Sets the position of a sound source.
	* - :doc:`/types/Script/getSoundSourcePosition/index`
	  - Returns the position of a sound source.
	* - :doc:`/types/Script/setSoundSourceGain/index`
	  - Sets the gain of a sound source.
	* - :doc:`/types/Script/getSoundSourceGain/index`
	  - Returns the gain of a sound source.
	* - :doc:`/types/Script/setSoundSourcePitch/index`
	  - Sets the pitch of a sound source.
	* - :doc:`/types/Script/getSoundSourcePitch/index`
	  - Returns the pitch of a sound source.
	* - :doc:`/types/Script/setSoundSourceLooping/index`
	  - Enables or disables looping on a sound source.
	* - :doc:`/types/Script/isSoundSourceLooping/index`
	  - Checks if a sound source is looping.
	* - :doc:`/types/Script/playAnimation/index`
	  - Plays an :doc:`/types/Animation/index` on an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/Script/pauseAnimation/index`
	  - Pauses an :doc:`/types/Animation/index` of an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/Script/stopAnimation/index`
	  - Stops an :doc:`/types/Animation/index` of an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/Script/setAnimationCurrentTime/index`
	  - Sets the current playing time of an :doc:`/types/Animation/index` played by an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/Script/isAnimationPlaying/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` is currently playing a certain :doc:`/types/Animation/index`.
	* - :doc:`/types/Script/drawUIText/index`
	  - Draws text on the User Interface.
	* - :doc:`/types/Script/drawUILine/index`
	  - Draws a line on the User Interface.
	* - :doc:`/types/Script/drawUIRectangle/index`
	  - Draws a rectangle on the User Interface.
	* - :doc:`/types/Script/drawUIImage/index`
	  - Draws an image on the User Interface.
	* - :doc:`/types/Script/setMaxFPS/index`
	  - Sets the maximum number of frames per second.
	* - :doc:`/types/Script/getMaxFPS/index`
	  - Returns the maximum number of frames per second.
	* - :doc:`/types/Script/executeJob/index`
	  - Launches a job to be executed by a worker thread.
	* - :doc:`/types/Script/dispatchJob/index`
	  - Launches a job to be executed by multiple worker threads.
	* - :doc:`/types/Script/waitAllThreads/index`
	  - Waits for all worker threads to finish their jobs.
	* - :doc:`/types/Script/getNumThreads/index`
	  - Returns the number of threads.
	* - :doc:`/types/Script/createServerSocket/index`
	  - Creates a :doc:`/types/ServerSocket/index`.
	* - :doc:`/types/Script/createClientSocket/index`
	  - Creates a :doc:`/types/ClientSocket/index`.
	* - :doc:`/types/Script/closeServerSocket/index`
	  - Closes a :doc:`/types/ServerSocket/index`.
	* - :doc:`/types/Script/closeClientSocket/index`
	  - Closes a :doc:`/types/ClientSocket/index`.
	* - :doc:`/types/Script/createScript/index`
	  - Creates a new :doc:`/types/Script/index` for a :doc:`/types/Scriptable/index` :doc:`/entity_component_system/component/index`.
	* - :doc:`/types/Script/startProfiling/index`
	  - Starts a profiling session.
	* - :doc:`/types/Script/getProfilingResults/index`
	  - Returns the result of the profiling.
	* - :doc:`/types/Script/endProfiling/index`
	  - Ends a profiling session and returns the result.
	* - :doc:`/types/Script/isProfilerRunning/index`
	  - Checks if the profiler is running.
	* - :doc:`/types/Script/startProfilingBlock/index`
	  - Starts a profiling block.
	* - :doc:`/types/Script/endProfilingBlock/index`
	  - Ends a profiling block.

.. toctree::
	:hidden:

	./init/index.rst
	./update/index.rst
	./destroy/index.rst

	./goToScene/index.rst
	./getCurrentScenePath/index.rst

	./createEntity/index.rst
	./destroyEntity/index.rst
	./destroyAllEntities/index.rst
	./destroyNonPersistentEntities/index.rst
	./entityExists/index.rst
	./getEntities/index.rst
	./setEntityName/index.rst
	./entityHasName/index.rst
	./getEntityName/index.rst
	./findEntityByName/index.rst
	./setEntityPersistence/index.rst
	./isEntityPersistent/index.rst
	./addEntityToEntityGroup/index.rst
	./removeEntityFromEntityGroup/index.rst
	./entityGroupExists/index.rst
	./isEntityInEntityGroup/index.rst
	./getEntitiesInEntityGroup/index.rst
	./getEntityGroupsOfEntity/index.rst
	./addEntityComponent/index.rst
	./removeEntityComponent/index.rst
	./hasEntityComponent/index.rst
	./getEntityComponent/index.rst
	
	./createModel/index.rst
	./loadModel/index.rst
	./getMeshID/index.rst
	./destroyModel/index.rst
	./findModelByName/index.rst
	./getModelName/index.rst
	./createMaterial/index.rst
	./loadMaterial/index.rst
	./destroyMaterial/index.rst
	./findMaterialByName/index.rst
	./getMaterialName/index.rst
	./createImage/index.rst
	./loadImage/index.rst
	./getImageID/index.rst
	./destroyImage/index.rst
	./findImageByName/index.rst
	./getImageName/index.rst
	./createFont/index.rst
	./loadFontBitmap/index.rst
	./loadFontSDF/index.rst
	./getFontID/index.rst
	./destroyFont/index.rst
	./findFontByName/index.rst
	./getFontName/index.rst
	./createSound/index.rst
	./loadSound/index.rst
	./getSoundID/index.rst
	./destroySound/index.rst
	./findSoundByName/index.rst
	./getSoundName/index.rst

	./getKeyState/index.rst
	./getMouseButtonState/index.rst
	./setCursorPosition/index.rst
	./getCursorPositionX/index.rst
	./getCursorPositionY/index.rst
	./getMouseScrollOffsetX/index.rst
	./getMouseScrollOffsetY/index.rst
	./setCursorVisibility/index.rst
	./isCursorVisible/index.rst
	./getConnectedGamepads/index.rst
	./getGamepadButtonState/index.rst
	./getGamepadStickAxisX/index.rst
	./getGamepadStickAxisY/index.rst
	./getGamepadLeftTrigger/index.rst
	./getGamepadRightTrigger/index.rst
	./getGamepadName/index.rst

	./openWindow/index.rst
	./isWindowOpen/index.rst
	./closeWindow/index.rst
	./getMainWindowID/index.rst
	./windowCount/index.rst
	./setWindowSize/index.rst
	./getWindowWidth/index.rst
	./getWindowHeight/index.rst
	./setWindowPosition/index.rst
	./getWindowPositionX/index.rst
	./getWindowPositionY/index.rst
	./setWindowFullscreen/index.rst
	./isWindowFullscreen/index.rst
	./setWindowBorderless/index.rst
	./isWindowBorderless/index.rst
	./setWindowResizable/index.rst
	./isWindowResizable/index.rst
	./setWindowOpacity/index.rst
	./getWindowOpacity/index.rst
	./getWindowDroppedFiles/index.rst
	./setWindowFocus/index.rst
	./isWindowFocused/index.rst
	./setWindowTitle/index.rst
	./getWindowTitle/index.rst
	./setWindowIcon/index.rst
	./getMonitorWidth/index.rst
	./getMonitorHeight/index.rst
	./getMonitorRefreshRate/index.rst
	./getMonitorDisplayScaling/index.rst

	./setBackgroundColor/index.rst
	./emitParticles/index.rst
	./destroyParticles/index.rst

	./playSound/index.rst
	./playSoundAtPosition/index.rst
	./resumeSoundSource/index.rst
	./pauseSoundSource/index.rst
	./stopSoundSource/index.rst
	./getSoundSourceState/index.rst
	./isSoundPlaying/index.rst
	./setSoundSourcePosition/index.rst
	./getSoundSourcePosition/index.rst
	./setSoundSourceGain/index.rst
	./getSoundSourceGain/index.rst
	./setSoundSourcePitch/index.rst
	./getSoundSourcePitch/index.rst
	./setSoundSourceLooping/index.rst
	./isSoundSourceLooping/index.rst

	./intersect/index.rst
	./raycast/index.rst
	./raycastAll/index.rst
	./setConstantForces/index.rst
	./getConstantForces/index.rst

	./playAnimation/index.rst
	./pauseAnimation/index.rst
	./stopAnimation/index.rst
	./setAnimationCurrentTime/index.rst
	./isAnimationPlaying/index.rst

	./drawUIText/index.rst
	./drawUILine/index.rst
	./drawUIRectangle/index.rst
	./drawUIImage/index.rst

	./setMaxFPS/index.rst
	./getMaxFPS/index.rst

	./executeJob/index
	./dispatchJob/index
	./waitAllThreads/index
	./getNumThreads/index

	./createServerSocket/index
	./createClientSocket/index
	./closeServerSocket/index
	./closeClientSocket/index

	./createScript/index

	./startProfiling/index
	./getProfilingResults/index
	./endProfiling/index
	./isProfilerRunning/index
	./startProfilingBlock/index
	./endProfilingBlock/index