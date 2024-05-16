destroyFont
===========

:doc:`/types/AssetManagerInterface/index`::destroyFont

Destroys a font.

Declaration
-----------

.. code-block:: cpp

	virtual void destroyFont(Font* font) = 0;

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
	  - :doc:`/types/Font/index`\*
	  - The address memory of the :doc:`/types/Font/index` to destroy.

Returns
-------

None.