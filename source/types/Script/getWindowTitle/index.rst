getWindowTitle
==============

:doc:`/types/Script/index`::getWindowTitle

Sets the window's title.

Declaration
-----------

.. code-block:: cpp

	void getWindowTitle(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to change the title of. By default, this window will be the main window.

Returns
-------

The window's title as a `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.