setMaxFPS
=========

:doc:`/types/FrameLimiterInterface/index`::setMaxFPS

Sets the maximum number of frames per second.

Declaration
-----------

.. code-block:: cpp

	virtual void setMaxFPS(uint32_t maxFPS) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - maxFPS
	  - uint32_t
	  - The maximum number of frames per second.

Returns
-------

None.

Notes
-----

A ``maxFPS`` of ``0`` removes the frames per second limit.