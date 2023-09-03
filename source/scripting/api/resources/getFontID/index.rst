getFontID
=========

ScriptingAPI::getFontID

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
	  - const Font&
	  - Font to load in the Graphics Module.

Returns
-------

A unique identifier for the font.

If the font could not be loaded, the returned value is ``NTSHENGN_FONT_UNKNOWN``.