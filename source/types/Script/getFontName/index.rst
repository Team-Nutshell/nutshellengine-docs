getFontName
===========

:doc:`/types/Script/index`::getFontName

Returns the name of the font.

Declaration
-----------

.. code-block:: cpp

	virtual std::string getFontName(const Font* font) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - font
	  - const :doc:`/types/Font/index`\*
	  - The :doc:`/types/Font/index` to get the name of.

Returns
-------

The name of the :doc:`/types/Font/index` if it exists, else, returns the empty string ``""``.