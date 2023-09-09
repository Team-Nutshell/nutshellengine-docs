setWindowSize
=============

:doc:`/types/WindowModuleInterface/index`::setWindowSize

Sets the size of the window.

Declaration
-----------

.. code-block:: cpp

	virtual void setWindowSize(WindowID windowID, int width, int height) = 0;

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
	  - The window to change the size of.
	* - width
	  - int
	  - The new width of the window.
	* - height
	  - int
	  - The new height of the window.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.