createImage
===========

:doc:`/types/AssetManagerInterface/index`::createImage

Creates an empty image and returns its pointer.

Declaration
-----------

.. code-block:: cpp

	virtual Image* createImage(const std::string& imageName) = 0;

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
	  - A unique name for the new :doc:`/types/Image/index`.

Returns
-------

A pointer to an empty :doc:`/types/Image/index`.