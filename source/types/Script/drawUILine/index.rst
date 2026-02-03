drawUILine
==========

:doc:`/types/Script/index`::drawUILine

Draws a line on the User Interface.

Declaration
-----------

.. code-block:: cpp

	void drawUILine(CoordinateType coordinateType, const Math::vec2& start, const Math::vec2& end, const Math::vec4& color = Math::vec4(1.0f, 1.0f, 1.0f, 1.0f));

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - coordinateType
	  - :doc:`/types/CoordinateType/index`
	  - The coordinate type used by ``start`` and ``end``.
	* - start
	  - const :doc:`/types/Math/index`::vec2&
	  - The starting point of the line.
	* - end
	  - const :doc:`/types/Math/index`::vec2&
	  - The ending point of the line.
	* - color
	  - const :doc:`/types/Math/index`::vec4&
	  - The color and opacity of the line.

Returns
-------

None.