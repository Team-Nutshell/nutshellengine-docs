loadImage
=========

:doc:`/types/AssetLoaderModuleInterface/index`::loadImage

Loads an image from a file.

Declaration
-----------

.. code-block:: cpp

	virtual bool loadImage(const std::string& filePath, Image& image) = 0;

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
	* - image
	  - :doc:`/types/Image/index`&
	  - The image to put the information in.

Returns
-------

``true`` if the image has been successfully loaded, else, if the image could not be loaded (for example: if the file does not exist, or the :doc:`/asset_manager/index` or :doc:`/module/asset_loader_module/index` does not support this image file format (including the case where there is no :doc:`/module/asset_loader_module/index`)), returns ``false``.