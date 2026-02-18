AudioModuleInterface
====================

*Inherits* :doc:`/types/ModuleInterface/index` *and* :doc:`/types/SystemModuleInterface/index`.

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/AudioModuleInterface/load/index`
	  - Loads a sound in the :doc:`/module/audio_module/index` and returns a unique identifier to this sound.
	* - :doc:`/types/AudioModuleInterface/playSound/index`
	  - Plays a global sound and returns a unique identifier to this sound source.
	* - :doc:`/types/AudioModuleInterface/playSoundAtPosition/index`
	  - Plays a sound at a certain position and returns a unique identifier to this sound source.
	* - :doc:`/types/AudioModuleInterface/resumeSoundSource/index`
	  - Resumes a paused sound source.
	* - :doc:`/types/AudioModuleInterface/pauseSoundSource/index`
	  - Pauses a playing sound source.
	* - :doc:`/types/AudioModuleInterface/stopSoundSource/index`
	  - Stops a playing or paused sound.
	* - :doc:`/types/AudioModuleInterface/getSoundSourceState/index`
	  - Returns the state of a sound source.
	* - :doc:`/types/AudioModuleInterface/isSoundPlaying/index`
	  - Checks if any sound source of a certain sound is playing.
	* - :doc:`/types/AudioModuleInterface/getSoundLength/index`
	  - Returns the length of a sound.
	* - :doc:`/types/AudioModuleInterface/setSoundSourceTime/index`
	  - Sets the current time of a sound source.
	* - :doc:`/types/AudioModuleInterface/getSoundSourceTime/index`
	  - Returns the current time of a sound source.
	* - :doc:`/types/AudioModuleInterface/setSoundSourcePosition/index`
	  - Sets the position of a sound source.
	* - :doc:`/types/AudioModuleInterface/getSoundSourcePosition/index`
	  - Returns the position of a sound source.
	* - :doc:`/types/AudioModuleInterface/setSoundSourceGain/index`
	  - Sets the gain of a sound source.
	* - :doc:`/types/AudioModuleInterface/getSoundSourceGain/index`
	  - Returns the gain of a sound source.
	* - :doc:`/types/AudioModuleInterface/setSoundSourcePitch/index`
	  - Sets the pitch of a sound source.
	* - :doc:`/types/AudioModuleInterface/getSoundSourcePitch/index`
	  - Returns the pitch of a sound source.
	* - :doc:`/types/AudioModuleInterface/setSoundSourceLooping/index`
	  - Enables or disables looping on a sound source.
	* - :doc:`/types/AudioModuleInterface/isSoundSourceLooping/index`
	  - Checks if a sound source is looping.
	* - :doc:`/types/AudioModuleInterface/setMasterGain/index`
	  - Sets the master gain.
	* - :doc:`/types/AudioModuleInterface/getMasterGain/index`
	  - Returns the master gain.

.. toctree::
	:hidden:

	./load/index.rst
	./playSound/index.rst
	./playSoundAtPosition/index.rst
	./resumeSoundSource/index.rst
	./pauseSoundSource/index.rst
	./stopSoundSource/index.rst
	./getSoundSourceState/index.rst
	./isSoundPlaying/index.rst
	./getSoundLength/index.rst
	./setSoundSourceTime/index.rst
	./getSoundSourceTime/index.rst
	./setSoundSourcePosition/index.rst
	./getSoundSourcePosition/index.rst
	./setSoundSourceGain/index.rst
	./getSoundSourceGain/index.rst
	./setSoundSourcePitch/index.rst
	./getSoundSourcePitch/index.rst
	./setSoundSourceLooping/index.rst
	./isSoundSourceLooping/index.rst
	./setMasterGain/index.rst
	./getMasterGain/index.rst