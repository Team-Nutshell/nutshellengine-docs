destroySound
============

:doc:`/types/AssetManagerInterface/index`::destroySound

Destroys a sound.

Declaration
-----------

.. code-block:: cpp

	virtual void destroySound(const std::string& soundName) = 0;

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
	  - The name of the :doc:`/types/Sound/index` to destroy.

Returns
-------

None.