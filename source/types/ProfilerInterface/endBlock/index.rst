endBlock
========

:doc:`/types/ProfilerInterface/index`::endBlock

Ends a profiling block.

Declaration
-----------

.. code-block:: cpp

	virtual void endBlock() = 0;

Parameters
----------

None.

Returns
-------

None.

Notes
-----

This function will end the last profiling block started with a :doc:`/types/Profiler/index`'s :doc:`/types/Profiler/startBlock/index` or a :doc:`/types/Script/index`'s :doc:`/types/Script/startProfilingBlock/index` function call.