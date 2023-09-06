setCursorPosition
=================

:doc:`/utils/Buffer/index`::setCursorPosition

Sets the Buffer's cursor's position.

Declaration
-----------

.. code-block:: cpp

	void setCursorPosition(size_t cursorPosition);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - cursorPosition
	  - size_t
	  - The position to set the :doc:`/utils/Buffer/index`'s cursor to.

Returns
-------

None.

Notes
-----

If ``cursorPosition`` exceeds the size of the :doc:`/utils/Buffer/index`, this function will throw an `std::out_of_range <https://en.cppreference.com/w/cpp/error/out_of_range>`_ exception.