getWindowTitle
==============

:doc:`/types/WindowModuleInterface/index`::getWindowTitle

Returns the window's title.

Declaration
-----------

.. code-block:: cpp

	virtual std::string getWindowTitle(WindowID windowID) = 0;

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
	  - The window to get the title of.

Returns
-------

The window's title as a `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`.