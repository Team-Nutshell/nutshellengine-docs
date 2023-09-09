setGain
=======

:doc:`/types/AudioModuleInterface/index`::setGain

Sets the gain of a sound.

Declaration
-----------

.. code-block:: cpp

	virtual void setGain(SoundID soundID, float newGain) = 0;

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
	  - The sound to check.
	* - newGain
	  - float
	  - The new gain of the sound.

Returns
-------

None.