Sound
=====

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - channels
	  - uint8_t
	  - The number of channels (1 for Mono, 2 for Stereo, etc.).
	* - sampleRate
	  - int32_t
	  - The sound's sample rate.
	* - bitsPerSample
	  - uint8_t
	  - The number of bits per sample.
	* - length
	  - float
	  - The length of the sound, **in seconds**.
	* - data
	  - `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_\<uint8_t>
	  - The sound's content.