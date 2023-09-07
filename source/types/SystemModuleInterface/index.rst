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
	  - Memory address to the :doc:`/modules/graphics_module/index`.
	* - physicsModule
	  - :doc:`/types/PhysicsModuleInterface/index`\*
	  - Memory address to the :doc:`/modules/physics_module/index`.
	* - windowModule
	  - :doc:`/types/WindowModuleInterface/index`\*
	  - Memory address to the :doc:`/modules/window_module/index`.
	* - audioModule
	  - :doc:`/types/AudioModuleInterface/index`\*
	  - Memory address to the :doc:`/modules/audio_module/index`.
	* - ecs
	  - :doc:`/types/ECS/index`\*
	  - Memory address to the :doc:`/entity_component_system/index`.
	* - assetManager
	  - :doc:`/types/AssetManager/index`\*
	  - Memory address to the :doc:`/asset_manager/index`.
	* - jobSystem
	  - :doc:`/types/JobSystem/index`\*
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
	* - :doc:`/types/SystemModuleInterface/init/index`
	  - Initialization function executed once, at program's launch.
	* - :doc:`/types/SystemModuleInterface/update/index`
	  - Update function executed once per frame.
	* - :doc:`/types/SystemModuleInterface/destroy/index`
	  - Destruction function executed once, at program's end.
	* - :doc:`/types/SystemModuleInterface/getComponentMask/index`
	  - Returns the tracked :doc:`Components </types/Component/index>`.

Notes
-----

``entities`` is the list of :doc:`Entities </types/Entity/index>` that have **at least** one of the :doc:`Components </types/Component/index>` tracked by this system.

.. toctree::
	:hidden:

	./init/index.rst
	./update/index.rst
	./destroy/index.rst
	./getComponentMask/index.rst