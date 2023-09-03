FontGlyph
=========

Declaration
-----------

.. code-block:: cpp

	struct FontGlyph {
		Math::vec2 positionTopLeft = { 0.0f, 0.0f };
		Math::vec2 positionBottomRight = { 0.0f, 0.0f };
		float positionAdvance = 0.0f;
		Math::vec2 uvTopLeft = { 0.0f, 0.0f };
		Math::vec2 uvBottomRight = { 0.0f, 0.0f };
	};

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - positionTopLeft
	  - Math::vec2
	  - The top-left position of the glyph's position.
	* - positionBottomRight
	  - Math::vec2
	  - The bottom-right position of the glyph's position.
	* - positionAdvance
	  - float
	  - The horizontal offset to add to the position when using this glyph.
	* - uvTopLeft
	  - Math::vec2
	  - The top-left position of the glyph on the font bitmap.
	* - uvBottomRight
	  - Math::vec2
	  - The bottom-right position of the glyph on the font bitmap.