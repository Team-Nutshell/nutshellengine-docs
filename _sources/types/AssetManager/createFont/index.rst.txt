createFont
==========

:doc:`/types/AssetManager/index`::createFont

Creates an empty font and returns its pointer.

Declaration
-----------

.. code-block:: cpp

	Font* createFont(const std::string& fontName);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - fontName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - A unique name for the new :doc:`/types/Font/index`.

Returns
-------

A pointer to an empty :doc:`/types/Font/index`.