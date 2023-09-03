Texture
=======

Declaration
-----------

.. code-block:: cpp

	struct Texture {
		Image* image = nullptr;
		ImageSampler imageSampler;
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
	* - image
	  - :doc:`/types/image/index`\*
	  - The texture's image.
	* - imageSampler
	  - :doc:`/types/image_sampler/index`\
	  - The texture's image sampler.