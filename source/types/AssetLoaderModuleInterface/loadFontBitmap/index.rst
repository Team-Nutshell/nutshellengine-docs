loadFontBitmap
==============

:doc:`/types/AssetLoaderModuleInterface/index`::loadFontBitmap

Loads a font from a file.

Declaration
-----------

.. code-block:: cpp

	virtual bool loadFontBitmap(const std::string& filePath, float fontHeight, Font& font) = 0;

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
	* - font
	  - :doc:`/types/Font/index`&
	  - The font to put the information in.

Returns
-------

``true`` if the font has been successfully loaded, else, if the font could not be loaded (for example: if the file does not exist, or the :doc:`/asset_manager/index` or :doc:`/module/asset_loader_module/index` does not support this font file format (including the case where there is no :doc:`/module/asset_loader_module/index`)), returns ``false``.

Notes
-----

A bitmap font does not scale well, but is more precise than SDF fonts when the text is small.