NativeWindowHandle
==================

Declaration
-----------

.. code-block:: cpp

	typedef void* NativeWindowHandle;

Notes
-----

Abstract data used to get a native window handle.

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Platform
	  - Type
	* - Windows
	  - `HWND <https://learn.microsoft.com/en-us/windows/win32/winprog/windows-data-types#HWND>`_
	* - Linux (Xlib)
	  - `Window <https://www.x.org/releases/current/doc/libX11/libX11/libX11.html>`_
	* - Linux (xcb)
	  - `xcb_window_t <https://www.x.org/releases/current/doc/man/man3/xcb_create_window.3.xhtml>`_
	* - Linux (Wayland)
	  - `struct wl_surface* <https://gitlab.freedesktop.org/wayland/wayland/-/blob/main/src/wayland-server.h>`_