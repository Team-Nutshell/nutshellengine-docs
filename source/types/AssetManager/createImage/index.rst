createImage
===========

:doc:`/types/AssetManager/index`::createImage

Creates an empty image and returns its pointer.

Declaration
-----------

.. code-block:: cpp

	Image* createImage(const std::string& imageName);

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