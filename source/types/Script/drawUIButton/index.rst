drawUIButton
============

:doc:`/types/Script/index`::drawUIButton

Draws a button on the User Interface and returns an :doc:`/types/Script/UIElementState/index`.

Declaration
-----------

.. code-block:: cpp

	UIElementState drawUIButton(const Math::vec2& position, const Math::vec2& size, const Math::vec4& color = Math::vec4(1.0f, 1.0f, 1.0f, 1.0f), InputMouseButton mouseButton = InputMouseButton::One);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - position
	  - const :doc:`/types/Math/index`::vec2&
	  - The position of the top-left corner of the button.
	* - size
	  - const :doc:`/types/Math/index`::vec2&
	  - The size of the button.
	* - color
	  - const :doc:`/types/Math/index`::vec4&
	  - The color and opacity of the button.
	* - mouseButton
	  - :doc:`/types/InputMouseButton/index`
	  - The mouse button to check.

Returns
-------

The :doc:`/types/Script/UIElementState/index` according to ``mouseButton``.

Notes
-----

The ``position`` is in pixels, with (0, 0) being the top-left corner of the UI.

The ``size`` is in pixels.