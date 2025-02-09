findSoundByName
===============

:doc:`/types/AssetManagerInterface/index`::findSoundByName

Returns the sound associated with the name.

Declaration
-----------

.. code-block:: cpp

	virtual Sound* findSoundByName(const std::string& soundName) = 0;

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
	  - The name of the :doc:`/types/Sound/index`.

Returns
-------

A pointer to a :doc:`/types/Sound/index` if the name is associated with a Sound, else, returns ``nullptr``.