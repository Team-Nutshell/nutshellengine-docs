WindowModuleInterface
=====================

*Inherits* :doc:`/types/ModuleInterface/index` *and* :doc:`/types/SystemModuleInterface/index`.

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/WindowModuleInterface/openWindow/index`
	  - Opens a new window.
	* - :doc:`/types/WindowModuleInterface/isWindowOpen/index`
	  - Checks if the window is opened.
	* - :doc:`/types/WindowModuleInterface/closeWindow/index`
	  - Closes the window. Closing the main window closes the application.
	* - :doc:`/types/WindowModuleInterface/getMainWindowID/index`
	  - Returns the unique identifier of the main window.
	* - :doc:`/types/WindowModuleInterface/windowCount/index`
	  - Returns the number of opened windows.
	* - :doc:`/types/WindowModuleInterface/setWindowSize/index`
	  - Sets the size of the window.
	* - :doc:`/types/WindowModuleInterface/getWindowWidth/index`
	  - Returns the width of the window.
	* - :doc:`/types/WindowModuleInterface/getWindowHeight/index`
	  - Returns the height of the window.
	* - :doc:`/types/WindowModuleInterface/setWindowPosition/index`
	  - Sets the position of the window on the screen.
	* - :doc:`/types/WindowModuleInterface/getWindowPositionX/index`
	  - Returns the horizontal position of the window on the screen.
	* - :doc:`/types/WindowModuleInterface/getWindowPositionY/index`
	  - Returns the vertical position of the window on the screen.
	* - :doc:`/types/WindowModuleInterface/setWindowFullscreen/index`
	  - Puts the window in fullscreen or windowed.
	* - :doc:`/types/WindowModuleInterface/isWindowFullscreen/index`
	  - Checks if the window is in fullscreen.
	* - :doc:`/types/WindowModuleInterface/setWindowBorderless/index`
	  - Removes or adds the window decorations.
	* - :doc:`/types/WindowModuleInterface/isWindowBorderless/index`
	  - Checks if the window decorations are shown.
	* - :doc:`/types/WindowModuleInterface/setWindowResizable/index`
	  - Enables or disables manual window resizing.
	* - :doc:`/types/WindowModuleInterface/isWindowResizable/index`
	  - Checks if the window can be manually resized.
	* - :doc:`/types/WindowModuleInterface/setWindowOpacity/index`
	  - Sets the window's opacity.
	* - :doc:`/types/WindowModuleInterface/getWindowOpacity/index`
	  - Returns the window's opacity.
	* - :doc:`/types/WindowModuleInterface/getWindowDroppedFiles/index`
	  - Returns the path to the files dropped on the window.
	* - :doc:`/types/WindowModuleInterface/setWindowFocus/index`
	  - Focuses the window.
	* - :doc:`/types/WindowModuleInterface/isWindowFocused/index`
	  - Checks if the window is focused.
	* - :doc:`/types/WindowModuleInterface/pollEvents/index`
	  - Polls the window system events.
	* - :doc:`/types/WindowModuleInterface/setWindowTitle/index`
	  - Sets the window's title.
	* - :doc:`/types/WindowModuleInterface/getWindowTitle/index`
	  - Returns the window's title.
	* - :doc:`/types/WindowModuleInterface/setWindowIcon/index`
	  - Sets the window's icon.
	* - :doc:`/types/WindowModuleInterface/getKeyState/index`
	  - Returns the state of a keyboard key.
	* - :doc:`/types/WindowModuleInterface/getMouseButtonState/index`
	  - Returns the state of a mouse button.
	* - :doc:`/types/WindowModuleInterface/setCursorPosition/index`
	  - Sets the mouse cursor position.
	* - :doc:`/types/WindowModuleInterface/getCursorPositionX/index`
	  - Returns the horizontal position of the window on the screen.
	* - :doc:`/types/WindowModuleInterface/getCursorPositionY/index`
	  - Returns the vertical position of the window on the screen.
	* - :doc:`/types/WindowModuleInterface/getMouseScrollOffsetX/index`
	  - Returns the horizontal mouse scroll offset between the last and current frame.
	* - :doc:`/types/WindowModuleInterface/getMouseScrollOffsetY/index`
	  - Returns the vertical mouse scroll offset between the last and current frame.
	* - :doc:`/types/WindowModuleInterface/setCursorVisibility/index`
	  - Sets the mouse cursor's visibility.
	* - :doc:`/types/WindowModuleInterface/isCursorVisible/index`
	  - Checks if the cursor is visible.
	* - :doc:`/types/WindowModuleInterface/getConnectedGamepads/index`
	  - Returns the list of connected gamepads.
	* - :doc:`/types/WindowModuleInterface/getGamepadButtonState/index`
	  - Returns the state of a gamepad button.
	* - :doc:`/types/WindowModuleInterface/getGamepadStickAxisX/index`
	  - Returns the value of the stick's horizontal axis, with -1.0 being left, 0.0 neutral and 1.0 right.
	* - :doc:`/types/WindowModuleInterface/getGamepadStickAxisY/index`
	  - Returns the value of the stick's vertical axis, with -1.0 being up, 0.0 neutral and 1.0 down.
	* - :doc:`/types/WindowModuleInterface/getGamepadLeftTrigger/index`
	  - Returns the value of the stick's left trigger, with 0.0 being neutral and 1.0 being fully pressed.
	* - :doc:`/types/WindowModuleInterface/getGamepadRightTrigger/index`
	  - Returns the value of the stick's right trigger, with 0.0 being neutral and 1.0 being fully pressed.
	* - :doc:`/types/WindowModuleInterface/getGamepadName/index`
	  - Returns the name of the gamepad.
	* - :doc:`/types/WindowModuleInterface/getMonitorWidth/index`
	  - Returns the width of the main monitor.
	* - :doc:`/types/WindowModuleInterface/getMonitorHeight/index`
	  - Returns the height of the main monitor.
	* - :doc:`/types/WindowModuleInterface/getMonitorDisplayScaling/index`
	  - Returns the display scaling of the main monitor.
	* - :doc:`/types/WindowModuleInterface/getWindowNativeHandle/index`
	  - Returns the native handle of the window.
	* - :doc:`/types/WindowModuleInterface/getWindowNativeAdditionalInformation/index`
	  - Returns a native additional information for the window.

.. toctree::
	:hidden:

	./openWindow/index.rst
	./isWindowOpen/index.rst
	./closeWindow/index.rst
	./getMainWindowID/index.rst
	./windowCount/index.rst
	./setWindowSize/index.rst
	./getWindowWidth/index.rst
	./getWindowHeight/index.rst
	./setWindowPosition/index.rst
	./getWindowPositionX/index.rst
	./getWindowPositionY/index.rst
	./setWindowFullscreen/index.rst
	./isWindowFullscreen/index.rst
	./setWindowBorderless/index.rst
	./isWindowBorderless/index.rst
	./setWindowResizable/index.rst
	./isWindowResizable/index.rst
	./setWindowOpacity/index.rst
	./getWindowOpacity/index.rst
	./getWindowDroppedFiles/index.rst
	./setWindowFocus/index.rst
	./isWindowFocused/index.rst
	./pollEvents/index.rst
	./setWindowTitle/index.rst
	./getWindowTitle/index.rst
	./setWindowIcon/index.rst
	./getKeyState/index.rst
	./getMouseButtonState/index.rst
	./setCursorPosition/index.rst
	./getCursorPositionX/index.rst
	./getCursorPositionY/index.rst
	./getMouseScrollOffsetX/index.rst
	./getMouseScrollOffsetY/index.rst
	./setCursorVisibility/index.rst
	./isCursorVisible/index.rst
	./getConnectedGamepads/index.rst
	./getGamepadButtonState/index.rst
	./getGamepadStickAxisX/index.rst
	./getGamepadStickAxisY/index.rst
	./getGamepadLeftTrigger/index.rst
	./getGamepadRightTrigger/index.rst
	./getGamepadName/index.rst
	./getMonitorWidth/index.rst
	./getMonitorHeight/index.rst
	./getMonitorRefreshRate/index.rst
	./getMonitorDisplayScaling/index.rst
	./getWindowNativeHandle/index.rst
	./getWindowNativeAdditionalInformation/index.rst