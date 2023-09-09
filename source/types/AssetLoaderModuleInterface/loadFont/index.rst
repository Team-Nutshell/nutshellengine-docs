loadFont
========

:doc:`/types/AssetLoaderModuleInterface/index`::loadFont

Loads a font from a file.

Declaration
-----------

.. code-block:: cpp

	virtual Font loadFont(const std::string& filePath, float fontHeight) = 0;

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
	* - fontHeight
	  - float
	  - Height of the font, in pt.

Returns
-------

A doc:`/types/Font/index` containing information about the loaded font.

If the font could not be loaded (for example: if the file does not exist, or the :doc:`/module/asset_loader_module/index` does not support this font file format), the returned :doc:`/types/Font/index` contains the structure's default information.