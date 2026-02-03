drawUIText
==========

:doc:`/types/GraphicsModuleInterface/index`::drawUIText

Draws text on the User Interface.

Declaration
-----------

.. code-block:: cpp

	virtual void drawUIText(FontID fontID, const std::wstring& text, AnchorPoint anchorPoint, CoordinateType coordinateType, const Math::vec2& position, const Math::vec2& scale, const Math::vec4& color) = 0;

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
	  - const `std::wstring <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The text to draw.
	* - anchorPoint
	  - :doc:`/types/AnchorPoint/index`
	  - The anchor point of the text.
	* - coordinateType
	  - :doc:`/types/CoordinateType/index`
	  - The coordinate type used by ``position``.
	* - position
	  - const :doc:`/types/Math/index`::vec2&
	  - The position where the text will start to draw.
	* - scale
	  - const :doc:`/types/Math/index`::vec2&
	  - The scale of the text.
	* - color
	  - const :doc:`/types/Math/index`::vec4&
	  - The color and opacity of the text.

Returns
-------

None.

Notes
-----

If ``text`` is directly written on the source code, the string literal "*L*" must be used, for example: *L"NutshellEngine"*.