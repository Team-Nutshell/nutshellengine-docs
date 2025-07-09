AssetLoaderModuleInterface
==========================

*Inherits* :doc:`/types/ModuleInterface/index`.

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - assetManager
	  - :doc:`/types/AssetManagerInterface/index`\*
	  - Memory address to the :doc:`/asset_manager/index`.

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/AssetLoaderModuleInterface/loadSound/index`
	  - Loads a sound from a file.
	* - :doc:`/types/AssetLoaderModuleInterface/loadModel/index`
	  - Loads a model from a file.
	* - :doc:`/types/AssetLoaderModuleInterface/loadMaterial/index`
	  - Loads a material from a file.
	* - :doc:`/types/AssetLoaderModuleInterface/loadImage/index`
	  - Loads an image from a file.
	* - :doc:`/types/AssetLoaderModuleInterface/loadFontBitmap/index`
	  - Loads a bitmap font from a file and returns a pointer to the loaded font.
	* - :doc:`/types/AssetLoaderModuleInterface/loadFontSDF/index`
	  - Loads a SDF font from a file and returns a pointer to the loaded font.

.. toctree::
	:hidden:

	./loadSound/index.rst
	./loadModel/index.rst
	./loadMaterial/index.rst
	./loadImage/index.rst
	./loadFontBitmap/index.rst
	./loadFontSDF/index.rst