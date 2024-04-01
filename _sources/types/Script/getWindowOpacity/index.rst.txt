getWindowOpacity
================

:doc:`/types/Script/index`::getWindowOpacity

Returns the window's opacity.

Declaration
-----------

.. code-block:: cpp

	float getWindowOpacity(WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

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
	  - The window to get the opacity of.

Returns
-------

The window's opacity, between ``0.0`` (transparent) and ``1.0`` (opaque).

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.