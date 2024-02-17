getWindowDroppedFiles
=====================

:doc:`/types/Script/index`::getWindowDroppedFiles

Returns the path to the files dropped on the window.

Declaration
-----------

.. code-block:: cpp

	std::vector<std::string> getWindowDroppedFiles(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window the files are dropped on.

Returns
-------

An `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_ of the paths of the files dropped on the window during the current frame.

If no file has been dropped on the window, the returned `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_ is empty.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.