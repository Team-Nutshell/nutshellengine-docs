createSound
===========

:doc:`/types/AssetManagerInterface/index`::createSound

Creates an empty sound and returns its pointer.

Declaration
-----------

.. code-block:: cpp

	virtual Sound* createSound(const std::string& soundName) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - soundName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - A unique name for the new :doc:`/types/Sound/index`.

Returns
-------

A pointer to an empty :doc:`/types/Sound/index`.