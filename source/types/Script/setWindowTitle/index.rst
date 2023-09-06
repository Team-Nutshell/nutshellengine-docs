setWindowTitle
==============

:doc:`/types/Script/index`::setWindowTitle

Sets the window's title.

Declaration
-----------

.. code-block:: cpp

	void setWindowTitle(const std::string& title, WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - title
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The new title of the window.
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window to change the title of.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.