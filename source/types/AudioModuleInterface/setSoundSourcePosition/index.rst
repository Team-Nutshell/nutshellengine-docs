setSoundSourcePosition
======================

:doc:`/types/AudioModuleInterface/index`::setSoundSourcePosition

Sets the position of a sound source.

Declaration
-----------

.. code-block:: cpp

	virtual void setSoundSourcePosition(SoundSourceID soundSourceID, const Math::vec3& newPosition) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - soundSourceID
	  - :doc:`/types/SoundSourceID/index`
	  - The sound source to change the position of.
	* - newPosition
	  - :doc:`/types/Math/index`::vec3
	  - The new position of the sound source.

Returns
-------

None.