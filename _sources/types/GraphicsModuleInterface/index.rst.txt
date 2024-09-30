GraphicsModuleInterface
=======================

*Inherits* :doc:`/types/ModuleInterface/index` *and* :doc:`/types/SystemModuleInterface/index`.

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/GraphicsModuleInterface/load/index`
	  - Loads a mesh, an image or a font in the :doc:`/module/graphics_module/index` and returns a unique identifier to this resource.
	* - :doc:`/types/GraphicsModuleInterface/setBackgroundColor/index`
	  - Sets the color of the background.
	* - :doc:`/types/GraphicsModuleInterface/playAnimation/index`
	  - Plays an :doc:`/types/Animation/index` on an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/GraphicsModuleInterface/pauseAnimation/index`
	  - Pauses an :doc:`/types/Animation/index` of an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/GraphicsModuleInterface/stopAnimation/index`
	  - Stops an :doc:`/types/Animation/index` of an :doc:`/entity_component_system/entity/index`.
	* - :doc:`/types/GraphicsModuleInterface/isAnimationPlaying/index`
	  - Checks if an :doc:`/entity_component_system/entity/index` is currently playing a certain :doc:`/types/Animation/index`.
	* - :doc:`/types/GraphicsModuleInterface/emitParticles/index`
	  - Emits particles described by a :doc:`/types/ParticleEmitter/index`.
	* - :doc:`/types/GraphicsModuleInterface/drawUIText/index`
	  - Draws text on the User Interface.
	* - :doc:`/types/GraphicsModuleInterface/drawUILine/index`
	  - Draws a line on the User Interface.
	* - :doc:`/types/GraphicsModuleInterface/drawUIRectangle/index`
	  - Draws a rectangle on the User Interface.
	* - :doc:`/types/GraphicsModuleInterface/drawUIImage/index`
	  - Draws an image on the User Interface.

.. toctree::
	:hidden:

	./load/index.rst
	./setBackgroundColor/index.rst
	./playAnimation/index.rst
	./pauseAnimation/index.rst
	./stopAnimation/index.rst
	./isAnimationPlaying/index.rst
	./emitParticles/index.rst
	./drawUIText/index.rst
	./drawUILine/index.rst
	./drawUIRectangle/index.rst
	./drawUIImage/index.rst