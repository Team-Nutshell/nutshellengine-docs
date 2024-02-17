getWindowDroppedFiles
=====================

:doc:`/types/WindowModuleInterface/index`::getWindowDroppedFiles

Returns the path to the files dropped on the window.

Declaration
-----------

.. code-block:: cpp

	virtual std::vector<std::string> getWindowDroppedFiles(WindowID windowID) = 0;

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