getImageName
============

:doc:`/types/AssetManagerInterface/index`::getImageName

Returns the name of the image.

Declaration
-----------

.. code-block:: cpp

	virtual std::string getImageName(const Image* image) = 0;

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
	  - const :doc:`/types/Image/index`\*
	  - The :doc:`/types/Image/index` to get the name of.

Returns
-------

The name of the :doc:`/types/Image/index` if it exists, else, returns the empty string ``""``.