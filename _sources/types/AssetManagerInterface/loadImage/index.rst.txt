loadImage
=========

:doc:`/types/AssetManagerInterface/index`::loadImage

Loads an image from a file and returns a pointer to the loaded image.

Declaration
-----------

.. code-block:: cpp

	virtual Image* loadImage(const std::string& filePath) = 0;

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

A pointer to an :doc:`/types/Image/index` containing information about the loaded image.

If the image could not be loaded (for example: if the file does not exist, or the :doc:`/asset_manager/index` or :doc:`/module/asset_loader_module/index` does not support this image file format (including the case where there is no :doc:`/module/asset_loader_module/index`)), the returned pointer is **nullptr**.