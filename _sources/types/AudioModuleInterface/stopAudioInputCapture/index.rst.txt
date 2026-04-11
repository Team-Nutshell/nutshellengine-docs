stopAudioInputCapture
=====================

:doc:`/types/AudioModuleInterface/index`::stopAudioInputCapture

Ends audio input capture.

Declaration
-----------

.. code-block:: cpp

	virtual SoundID stopAudioInputCapture() = 0;

Parameters
----------

None.

Returns
-------

The :doc:`/types/SoundID` of the captured sound.

Notes
-----

End the audio input capture started with :doc:`/scripting/api/index`'s function :doc:`/types/Script/startAudioInputCapture/index` or the :doc:`/module/audio_module/index`'s :doc:`/types/AudioModuleInterface/startAudioInputCapture/index` function.