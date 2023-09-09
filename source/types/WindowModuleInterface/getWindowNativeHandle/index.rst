getWindowNativeHandle
=====================

:doc:`/types/WindowModuleInterface/index`::getWindowNativeHandle

Returns the native handle of the window.

Declaration
-----------

.. code-block:: cpp

	virtual NativeWindowHandle getWindowNativeHandle(WindowID windowID) = 0;

Parameters
----------

None.

Returns
-------

The :doc:`/types/NativeWindowHandle/index` of the window, depending on the platform and window system.