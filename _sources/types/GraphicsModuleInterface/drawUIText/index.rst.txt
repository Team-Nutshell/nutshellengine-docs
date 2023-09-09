drawUIText
==========

:doc:`/types/GraphicsModuleInterface/index`::drawUIText

Draws text on the User Interface.

Declaration
-----------

.. code-block:: cpp

	virtual void drawUIText(FontID fontID, const std::string& text, const Math::vec2& position, const Math::vec4& color) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - fontID
	  - :doc:`/types/FontID/index`
	  - The font to use to draw the text.
	* - text
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The text to draw.
	* - position
	  - const :doc:`/types/Math/index`::vec2&
	  - The position where the text will start to draw.
	* - color
	  - const :doc:`/types/Math/index`::vec4&
	  - The color and opacity of the text.

Returns
-------

None.

Notes
-----

The text must only contain ASCII characters.

The ``position`` is in pixels, with (0, 0) being the top-left corner of the UI.