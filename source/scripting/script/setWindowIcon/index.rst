setWindowIcon
=============

:doc:`/scripting/script/index`::setWindowIcon

Sets the window's icon.

Declaration
-----------

.. code-block:: cpp

	void setWindowIcon(const Image& image, WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - const :doc:`/types/Image/index`\&
	  - The new icon of the window.
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window to change the title of.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.