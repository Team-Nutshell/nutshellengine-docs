.ntop - Options
===============

**.ntop** is an **option** format. It is used to define the application's launch options.

*.ntop* is in the JSON format, and can be read and written using :doc:`/types/JSON/index`.

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	  - Possible values
	* - windowTitle
	  - String
	  - The main window's title.
	  - Any string.
	* - windowIconImagePath
	  - String
	  - The main window's icon path.
	  - A path to an image.
	* - maxFPS
	  - Number
	  - The maximum number of frames per second.
	  - Any integer number. 0 means no maximum.
	* - firstScenePath
	  - String
	  - The path to the application's first scene (:doc:`/file_formats/ntsn/index`).
	  - A path to a scene file.
