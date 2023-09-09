setWindowIcon
=============

:doc:`/types/WindowModuleInterface/index`::setWindowIcon

Sets the window's icon.

Declaration
-----------

.. code-block:: cpp

	virtual void setWindowIcon(WindowID windowID, const Image& image) = 0;

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
	  - const :doc:`/types/Image/index`\&
	  - The new icon of the window.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.