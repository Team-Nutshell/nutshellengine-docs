getSoundName
============

:doc:`/types/AssetManagerInterface/index`::getSoundName

Returns the name of the sound.

Declaration
-----------

.. code-block:: cpp

	virtual std::string getSoundName(const Sound* sound) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - sound
	  - const :doc:`/types/Sound/index`\*
	  - The :doc:`/types/Sound/index` to get the name of.

Returns
-------

The name of the :doc:`/types/Sound/index` if it exists, else, returns the empty string ``""``.