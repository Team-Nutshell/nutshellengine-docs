getFontID
=========

:doc:`/types/Script/index`::getFontID

Loads a font in the Graphics Module and returns a unique identifier to this font.

Declaration
-----------

.. code-block:: cpp

	FontID getFontID(const Font& font);

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
	  - const :doc:`/types/Font/index`\&
	  - Font to load in the Graphics Module.

Returns
-------

A unique :doc:`/types/FontID/index` identifier for the font.

If the font could not be loaded, the returned value is ``NTSHENGN_FONT_UNKNOWN``.