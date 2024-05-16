getProfilingResults
===================

:doc:`/types/Script/index`::getProfilingResults

Returns the result of the profiling.

Declaration
-----------

.. code-block:: cpp

	ProfilerResultNode getProfilingResults();

Parameters
----------

None.

Returns
-------

The root's :doc:`/types/ProfilerResultNode/index`. It represents the complete profiling session, with its ``name`` equal to the one given with the previous :doc:`/types/Profiler/index`'s :doc:`/types/Profiler/start/index` or :doc:`/types/Script/index`'s :doc:`/types/Script/startProfiling/index` function call and ``totalTime`` being the time of the entire session. ``meanTime``, ``minTimeIndex``, ``minTime``, ``maxTimeIndex`` and ``maxTime`` will be equal to 0.

The profiling blocks of this session are hierarchically available in ``children``.