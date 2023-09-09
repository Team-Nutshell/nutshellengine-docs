loadSound
=========

:doc:`/types/AssetLoaderModuleInterface/index`::loadSound

Loads a sound from a file.

Declaration
-----------

.. code-block:: cpp

	virtual Sound loadSound(const std::string& filePath) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - filePath
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - Path to the file to load.

Returns
-------

A :doc:`/types/Sound/index` containing information about the loaded sound.

If the sound could not be loaded (for example: if the file does not exist, or the :doc:`/module/asset_loader_module/index` does not support this sound file format), the returned :doc:`/types/Sound/index` contains the structure's default information.