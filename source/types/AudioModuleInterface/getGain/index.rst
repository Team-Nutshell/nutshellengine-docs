getGain
=======

:doc:`/types/AudioModuleInterface/getGain/index`::getGain

Returns the gain of a sound.

Declaration
-----------

.. code-block:: cpp

	virtual float getGain(SoundID soundID) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - soundID
	  - :doc:`/types/SoundID/index`
	  - The sound to get the gain of.

Returns
-------

The gain of the sound.