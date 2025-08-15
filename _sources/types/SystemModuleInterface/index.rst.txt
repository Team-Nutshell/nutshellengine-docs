SystemModuleInterface
=====================

*Inherits* :doc:`/types/System/index`.

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
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
	* - platformModule
	  - :doc:`/types/PlatformModuleInterface/index`\*
	  - Memory address to the :doc:`/module/platform_module/index`.
	* - ecs
	  - :doc:`/types/ECSInterface/index`\*
	  - Memory address to the :doc:`/entity_component_system/index`.
	* - assetManager
	  - :doc:`/types/AssetManagerInterface/index`\*
	  - Memory address to the :doc:`/asset_manager/index`.
	* - jobSystem
	  - :doc:`/types/JobSystemInterface/index`\*
	  - Memory address to the :doc:`/job_system/index`.

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/SystemModuleInterface/getComponentMask/index`
	  - Returns the tracked :doc:`Components </types/Component/index>`.

.. toctree::
	:hidden:

	./getComponentMask/index.rst