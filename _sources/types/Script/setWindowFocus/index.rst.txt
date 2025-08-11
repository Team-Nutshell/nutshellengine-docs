setWindowFocus
==============

:doc:`/types/Script/index`::setWindowFocus

Focuses the window.

Declaration
-----------

.. code-block:: cpp

	void setWindowFocus(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to focus. By default, this window will be the main window.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.