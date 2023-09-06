drawUILine
==========

:doc:`/scripting/script/index`::drawUILine

Draws a line on the User Interface.

Declaration
-----------

.. code-block:: cpp

	void drawUILine(const Math::vec2& start, const Math::vec2& end, const Math::vec4& color = Math::vec4(1.0f, 1.0f, 1.0f, 1.0f));

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - start
	  - const :doc:`/utils/Math/index`::vec2&
	  - The starting point of the line.
	* - end
	  - const :doc:`/utils/Math/index`::vec2&
	  - The ending point of the line.
	* - color
	  - const :doc:`/utils/Math/index`::vec4&
	  - The color and opacity of the line.

Returns
-------

None.

Notes
-----

The ``start`` and ``end`` positions are in pixels, with (0, 0) being the top-left corner of the UI.