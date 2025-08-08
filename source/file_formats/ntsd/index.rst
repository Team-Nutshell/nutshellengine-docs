.ntsd - Sound
=============

**.ntsd** is a **sound** format, like *.wav or .ogg*, but made to mimick the :doc:`/types/Sound/index` structure. The data is **uncompressed** so it is only recommended to use it in small programs.

*.ntsd* is in the JSON format, and can be read and written using :doc:`/types/JSON/index`.

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	  - Possible values
	* - channels
	  - Number
	  - The number of channels.
	  - 1 for Stereo, 2 for Mono or more.
	* - sampleRate
	  - Number
	  - The sound's sample rate.
	  - Any integer number.
	* - bitsPerSample
	  - Number
	  - The number of bits per sample.
	  - Any integer number.
	* - data
	  - Array of Numbers
	  - The content of the sound.
	  - Any array of are number.
