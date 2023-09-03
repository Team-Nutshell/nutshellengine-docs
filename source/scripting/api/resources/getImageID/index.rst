getImageID
==========

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
	  - const Image&
	  - Image to load in the Graphics Module.

Returns
-------

A unique identifier for the image.

If the image could not be loaded, the returned value is ``NTSHENGN_IMAGE_UNKNOWN``.