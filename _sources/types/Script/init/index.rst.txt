init
====

:doc:`/types/Script/index`::init

Initialization function executed once, when the :doc:`/types/Script/index` is created.

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

This function must be overloaded when creating a :doc:`/types/Script/index` and is executed once, when the :doc:`/types/Scriptable/index` Component is added to an :doc:`/types/Entity/index`.