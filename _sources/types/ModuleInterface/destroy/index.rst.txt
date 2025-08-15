destroy
=======

:doc:`/types/ModuleInterface/index`::destroy

Destruction function executed once, at program's end.

Declaration
-----------

.. code-block:: cpp

	virtual void destroy() = 0;

Parameters
----------

None.

Returns
-------

None.

Notes
-----

This function must be overloaded when creating a :doc:`/types/ModuleInterface/index` and is executed once, at program's end.