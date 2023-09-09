loadImage
=========

:doc:`/types/AssetLoaderModuleInterface/index`::loadImage

Loads an image from a file.

Declaration
-----------

.. code-block:: cpp

	virtual Image loadImage(const std::string& filePath) = 0;

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
	  - Path to the file to load.

Returns
-------

An :doc:`/types/Image/index` containing information about the loaded image.

If the image could not be loaded (for example: if the file does not exist, or the :doc:`/module/asset_loader_module/index` does not support this image file format), the returned :doc:`/types/Image/index` contains the structure's default information.