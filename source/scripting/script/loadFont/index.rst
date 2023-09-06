loadFont
========

:doc:`/scripting/script/index`::loadFont

Loads a font from a file in the AssetManager and returns a pointer to the loaded font.

Declaration
-----------

.. code-block:: cpp

	Font* loadFont(const std::string& filePath, float fontHeight);

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

If the font could not be loaded (for example: if the file does not exist, or the Asset Manager or Asset Loader Module does not support this image file format), the returned pointer is **nullptr**.