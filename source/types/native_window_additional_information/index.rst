NativeWindowAdditionalInformation
=================================

Declaration
-----------

.. code-block:: cpp

	typedef void* NativeWindowAdditionalInformation;

Notes
-----

Abstract data used to get a native window additional information.

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Platform
	  - Type
	* - Windows
	  - `HINSTANCE <https://learn.microsoft.com/en-us/windows/win32/winprog/windows-data-types#HINSTANCE>`_
	* - Linux (Xlib)
	  - `Display* <https://www.x.org/releases/current/doc/libX11/libX11/libX11.html>`_
	* - Linux (xcb)
	  - `xcb_connection_t* <https://www.x.org/releases/current/doc/man/man3/xcb_create_window.3.xhtml>`_
	* - Linux (Wayland)
	  - `struct wl_display* <https://gitlab.freedesktop.org/wayland/wayland/-/blob/main/src/wayland-server.h>`_