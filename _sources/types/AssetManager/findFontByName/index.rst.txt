findFontByName
==============

:doc:`/types/AssetManager/index`::findFontByName

Returns the font associated with the name.

Declaration
-----------

.. code-block:: cpp

	Font* findFontByName(const std::string& fontName);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - fontName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The name of the :doc:`/types/Font/index`.

Returns
-------

A pointer to a :doc:`/types/Font/index` if the name is associated with a font, else, returns ``nullptr``.