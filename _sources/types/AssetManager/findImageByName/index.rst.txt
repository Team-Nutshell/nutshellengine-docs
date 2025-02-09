findImageByName
===============

:doc:`/types/AssetManager/index`::findImageByName

Returns the image associated with the name.

Declaration
-----------

.. code-block:: cpp

	Image* findImageByName(const std::string& imageName);

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
	  - The name of the :doc:`/types/Image/index`.

Returns
-------

A pointer to an :doc:`/types/Image/index` if the name is associated with a image, else, returns ``nullptr``.