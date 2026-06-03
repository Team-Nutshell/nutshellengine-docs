ModuleInterface
===============

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
	* - assetManager
	  - :doc:`/types/AssetManagerInterface/index`\*
	  - Memory address to the :doc:`/asset_manager/index`.
	* - jobSystem
	  - :doc:`/types/JobSystemInterface/index`\*
	  - Memory address to the :doc:`/job_system/index`.
	* - commandLine
	  - :doc:`/types/CommandLineInterface/index`\*
	  - Memory address to the :doc:`/types/CommandLine/index`.
	* - profiler
	  - :doc:`/types/ProfilerInterface/index`\*
	  - Memory address to the profiler.

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/ModuleInterface/constructor/index`
	  - Constructs a :doc:`/types/ModuleInterface/index`.
	* - :doc:`/types/ModuleInterface/getType/index`
	  - Returns the :doc:`/module/index`'s :doc:`/types/ModuleType/index`.
	* - :doc:`/types/ModuleInterface/getName/index`
	  - Returns the :doc:`/module/index`'s name.
	* - :doc:`/types/SystemModuleInterface/init/index`
	  - Initialization function executed once, at program's launch.
	* - :doc:`/types/SystemModuleInterface/update/index`
	  - Update function executed once per frame.
	* - :doc:`/types/SystemModuleInterface/destroy/index`
	  - Destruction function executed once, at program's end.

Notes
-----

ModuleInterface is the base class of all :doc:`Modules </module/index>`.

.. toctree::
	:hidden:

	./constructor/index.rst
	./getType/index.rst
	./getName/index.rst
	./init/index.rst
	./update/index.rst
	./destroy/index.rst