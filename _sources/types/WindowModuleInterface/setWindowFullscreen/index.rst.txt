setWindowFullscreen
===================

:doc:`/types/WindowModuleInterface/index`::setWindowFullscreen

Puts the window in fullscreen or windowed.

Declaration
-----------

.. code-block:: cpp

	virtual void setWindowFullscreen(WindowID windowID, bool fullscreen) = 0;

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
	  - The window to change the fullscreen mode of.
	* - fullscreen
	  - bool
	  - Fullscreen (``true``) or windowed (``false``).

Returns
-------

None.