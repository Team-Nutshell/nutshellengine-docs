destroyFont
===========

:doc:`/types/AssetManagerInterface/index`::destroyFont

Destroys a font.

Declaration
-----------

.. code-block:: cpp

	virtual void destroyFont(const std::string& fontName) = 0;

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
	  - The name of the :doc:`/types/Font/index` to destroy.

Returns
-------

None.