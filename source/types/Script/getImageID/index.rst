getImageID
==========

:doc:`/types/Script/index`::getImageID

Loads an image in the :doc:`/module/graphics_module/index` and returns a unique identifier to this image.

Declaration
-----------

.. code-block:: cpp

	ImageID getImageID(const Image& image);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - image
	  - const :doc:`/types/Image/index`\&
	  - Image to load in the :doc:`/module/graphics_module/index`.

Returns
-------

A unique :doc:`/types/ImageID/index` identifier for the image.

If the image could not be loaded, the returned value is ``NTSHENGN_IMAGE_UNKNOWN``.