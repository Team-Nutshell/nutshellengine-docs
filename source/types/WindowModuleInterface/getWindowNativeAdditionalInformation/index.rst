getWindowNativeAdditionalInformation
====================================

:doc:`/types/WindowModuleInterface/index`::getWindowNativeAdditionalInformation

Returns a native additional information for the window.

Declaration
-----------

.. code-block:: cpp

	virtual NativeWindowAdditionalInformation getWindowNativeAdditionalInformation(WindowID windowID) = 0;

Parameters
----------

None.

Returns
-------

A :doc:`/types/NativeWindowAdditionalInformation/index` of the window, depending on the platform and window system.