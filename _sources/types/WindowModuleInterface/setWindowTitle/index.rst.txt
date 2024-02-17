setWindowTitle
==============

:doc:`/types/WindowModuleInterface/index`::setWindowTitle

Sets the window's title.

Declaration
-----------

.. code-block:: cpp

	virtual void setWindowTitle(WindowID windowID, const std::string& title) = 0;

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
	  - The window to change the title of.
	* - title
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The new title of the window.

Returns
-------

None.