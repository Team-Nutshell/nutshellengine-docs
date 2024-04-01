setWindowOpacity
================

:doc:`/types/WindowModuleInterface/index`::setWindowOpacity

Sets the window's opacity.

Declaration
-----------

.. code-block:: cpp

	virtual void setWindowOpacity(WindowID windowID, float opacity) = 0;

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
	  - The window to change the opacity of.
	* - opacity
	  - float
	  - The window's opacity, between ``0.0`` (transparent) and ``1.0`` (opaque).

Returns
-------

None.