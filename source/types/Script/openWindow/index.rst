openWindow
==========

:doc:`/types/Script/index`::openWindow

Opens a new window.

Declaration
-----------

.. code-block:: cpp

	WindowID openWindow(int width, int height, const std::string& title);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - width
	  - int
	  - The width of the window to open.
	* - height
	  - int
	  - The height of the window to open.
	* - title
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The title of the window to open.

Returns
-------

A unique :doc:`/types/WindowID/index`.