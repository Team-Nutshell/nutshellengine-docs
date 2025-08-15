init
====

:doc:`/types/ModuleInterface/index`::init

Initialization function executed once, at program's launch.

Declaration
-----------

.. code-block:: cpp

	virtual void init() = 0;

Parameters
----------

None.

Returns
-------

None.

Notes
-----

This function must be overloaded when creating a :doc:`/types/ModuleInterface/index` and is executed once, when the program launches.