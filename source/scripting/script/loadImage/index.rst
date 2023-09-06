loadImage
=========

:doc:`/scripting/script/index`::loadImage

Loads an image from a file in the AssetManager and returns a pointer to the loaded image.

Declaration
-----------

.. code-block:: cpp

	Image* loadImage(const std::string& filePath);

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

If the image could not be loaded (for example: if the file does not exist, or the Asset Manager or Asset Loader Module does not support this image file format), the returned pointer is **nullptr**.