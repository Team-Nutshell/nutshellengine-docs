destroySound
============

:doc:`/types/AssetManagerInterface/index`::destroySound

Destroys a sound.

Declaration
-----------

.. code-block:: cpp

	virtual void destroySound(Sound* sound) = 0;

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
	  - :doc:`/types/Sound/index`\*
	  - The address memory of the :doc:`/types/Sound/index` to destroy.

Returns
-------

None.