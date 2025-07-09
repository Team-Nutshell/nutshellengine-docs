drawUIText
==========

:doc:`/types/Script/index`::drawUIText

Draws text on the User Interface.

Declaration
-----------

.. code-block:: cpp

	void drawUIText(FontID fontID, const std::wstring& text, const Math::vec2& position, const Math::vec2& scale = Math::vec2(0.0f, 0.0f), const Math::vec4& color = Math::vec4(0.0f, 0.0f, 0.0f, 1.0f));

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

The ``position`` is in pixels, with (0, 0) being the top-left corner of the UI.

====

Draws text on the User Interface.

Declaration
-----------

.. code-block:: cpp

	void drawUIText(FontID fontID, const std::string& text, const Math::vec2& position, const Math::vec2& scale = Math::vec2(0.0f, 0.0f), const Math::vec4& color = Math::vec4(0.0f, 0.0f, 0.0f, 1.0f));

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

The ``position`` is in pixels, with (0, 0) being the top-left corner of the UI.