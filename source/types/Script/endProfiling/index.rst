endProfiling
============

:doc:`/types/Script/index`::endProfiling

Ends a profiling session and returns the result.

Declaration
-----------

.. code-block:: cpp

	ProfilerResultNode endProfiling();

Parameters
----------

None.

Returns
-------

The root's :doc:`/types/ProfilerResultNode/index`. It represents the complete profiling session, with its ``name`` equal to the one given with the previous :doc:`/types/Profiler/index`'s :doc:`/types/Profiler/start/index` or :doc:`/types/Script/index`'s :doc:`/types/Script/startProfiling/index` function call and ``totalTime`` being the time of the entire session. ``meanTime``, ``minTimeIndex``, ``minTime``, ``maxTimeIndex`` and ``maxTime`` will be equal to 0.

The profiling blocks of this session are hierarchically available in ``children``.

This function will end the profiling session and reset the profiler's times, the profiler will need to be started again with :doc:`/types/Profiler/index`'s :doc:`/types/Profiler/start/index` or :doc:`/types/Script/index`'s :doc:`/types/Script/startProfiling/index` functions if needed.