loadFontBitmap
==============

:doc:`/types/AssetManager/index`::loadFontBitmap

Loads a font from a file and returns a pointer to the loaded font.

Declaration
-----------

.. code-block:: cpp

	Font* loadFontBitmap(const std::string& filePath, float fontHeight);

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

A pointer to a :doc:`/types/Font/index` containing information about the loaded font.

If the font could not be loaded (for example: if the file does not exist, or the :doc:`/asset_manager/index` or :doc:`/module/asset_loader_module/index` does not support this font file format (including the case where there is no :doc:`/module/asset_loader_module/index`)), the returned pointer is **nullptr**.

A bitmap font does not scale well, but is more precise than SDF fonts when the text is small.