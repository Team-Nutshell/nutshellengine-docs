destroyImage
============

:doc:`/types/AssetManagerInterface/index`::destroyImage

Destroys an image.

Declaration
-----------

.. code-block:: cpp

	virtual void destroyImage(const std::string& imageName) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - imageName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The name of the :doc:`/types/Image/index` to destroy.

Returns
-------

None.