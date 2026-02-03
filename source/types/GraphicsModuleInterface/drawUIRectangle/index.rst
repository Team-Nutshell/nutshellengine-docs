drawUIRectangle
===============

:doc:`/types/GraphicsModuleInterface/index`::drawUIRectangle

Draws a rectangle on the User Interface.

Declaration
-----------

.. code-block:: cpp

	virtual void drawUIRectangle(CoordinateType coordinateType, const Math::vec2& position, const Math::vec2& size, const Math::vec4& color) = 0;

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
	  - The coordinate type used by ``position`` and ``size``.
	* - position
	  - const :doc:`/types/Math/index`::vec2&
	  - The position of the top-left corner of the rectangle.
	* - size
	  - const :doc:`/types/Math/index`::vec2&
	  - The size of the rectangle.
	* - color
	  - const :doc:`/types/Math/index`::vec4&
	  - The color and opacity of the rectangle.

Returns
-------

None.