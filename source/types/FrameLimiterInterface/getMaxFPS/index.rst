getMaxFPS
=========

:doc:`/types/FrameLimiterInterface/index`::getMaxFPS

Returns the maximum number of frames per second.

Declaration
-----------

.. code-block:: cpp

	virtual uint32_t getMaxFPS() = 0;

Parameters
----------

None.

Returns
-------

The maximum number of frames per second. A value of ``0`` means that the number of frames per second is not limited.