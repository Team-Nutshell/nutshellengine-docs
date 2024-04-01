setWindowOpacity
================

:doc:`/types/Script/index`::setWindowOpacity

Sets the window's opacity.

Declaration
-----------

.. code-block:: cpp

	void setWindowOpacity(float opacity, WindowID windowID = NTSHENGN_WINDOW_UNKNOWN);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - opacity
	  - float
	  - The window's opacity, between ``0.0`` (transparent) and ``1.0`` (opaque).
	* - windowID
	  - :doc:`/types/WindowID/index`
	  - The window to change the opacity of.

Returns
-------

None.

Notes
-----

The main window will be used if ``windowID`` is equal to ``NTSHENGN_WINDOW_UNKNOWN``.