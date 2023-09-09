drawUIImage
===========

:doc:`/types/GraphicsModuleInterface/index`::drawUIImage

Draws an image on the User Interface.

Declaration
-----------

.. code-block:: cpp

	virtual void drawUIImage(ImageID imageID, ImageSamplerFilter imageSamplerFilter, const Math::vec2& position, float rotation, const Math::vec2& scale, const Math::vec4& color) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - imageID
	  - :doc:`/types/ImageID/index`
	  - The image to draw.
	* - imageSamplerFilter
	  - :doc:`/types/ImageSamplerFilter/index`
	  - The image sampler filter to use for the image.
	* - position
	  - const :doc:`/types/Math/index`::vec2&
	  - The position of the image. The origin of the image is as its center.
	* - rotation
	  - float
	  - The angle in radians the image will be rotated with.
	* - scale
	  - const :doc:`/types/Math/index`::vec2&
	  - The scale of the image.
	* - color
	  - const :doc:`/types/Math/index`::vec4&
	  - The color and opacity the image will be multiplied with.

Returns
-------

None.

Notes
-----

The ``position`` is in pixels, with (0, 0) being the top-left corner of the UI.

If a ``scale``'s axis (x or y) is negative, the image will be flipped. For example, if ``scale`` is equal to ``Math::vec2(-1.0f, 1.0f)``, the image will have its original proportion but will be flipped horizontally.