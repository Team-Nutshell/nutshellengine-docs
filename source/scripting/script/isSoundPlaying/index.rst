isSoundPlaying
==============

:doc:`/scripting/script/index`::isSoundPlaying

Checks if a sound is currently playing.

Declaration
-----------

.. code-block:: cpp

	bool isSoundPlaying(SoundID soundID);

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

Returns
-------

``true`` if the sound is currently playing, else, returns ``false``.

A sound is not currently playing if:

- It was never played before,
- It ended,
- It was paused using :doc:`/scripting/script/pauseSound/index`.
- It was stopped using :doc:`/scripting/script/stopSound/index`.