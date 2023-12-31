getMonitorDisplayScaling
========================

:doc:`/types/WindowModuleInterface/index`::getMonitorDisplayScaling

Returns the display scaling of the main monitor.

Declaration
-----------

.. code-block:: cpp

	virtual float getMonitorDisplayScaling() = 0;

Parameters
----------

None.

Returns
-------

The display scaling of the main monitor. By default, the value is ``1.0f``. A display scaling of, for example, 150% will result in a value of ``1.5f``.