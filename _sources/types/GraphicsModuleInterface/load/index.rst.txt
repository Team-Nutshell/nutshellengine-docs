load
====

:doc:`/types/GraphicsModuleInterface/index`::load

Loads a mesh in the :doc:`/module/graphics_module/index` and returns a unique identifier to this mesh.

Declaration
-----------

.. code-block:: cpp

	virtual MeshID load(const Mesh& mesh) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - mesh
	  - const :doc:`/types/Mesh/index`\&
	  - Mesh to load in the :doc:`/module/graphics_module/index`.

Returns
-------

A unique :doc:`/types/MeshID/index` identifier for the mesh.

If the mesh could not be loaded, the returned value is ``NTSHENGN_MESH_UNKNOWN``.

====

Loads an image in the :doc:`/module/graphics_module/index` and returns a unique identifier to this image.

Declaration
-----------

.. code-block:: cpp

	virtual ImageID load(const Image& image) = 0;

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

====

Loads a font in the :doc:`/module/graphics_module/index` and returns a unique identifier to this font.

Declaration
-----------

.. code-block:: cpp

	virtual FontID load(const Font& font) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - font
	  - const :doc:`/types/Font/index`\&
	  - Font to load in the :doc:`/module/graphics_module/index`.

Returns
-------

A unique :doc:`/types/FontID/index` identifier for the font.

If the font could not be loaded, the returned value is ``NTSHENGN_FONT_UNKNOWN``.