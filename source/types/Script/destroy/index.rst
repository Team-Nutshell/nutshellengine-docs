destroy
=======

:doc:`/types/Script/index`::destroy

Destruction function executed once, when the :doc:`/types/Script/index` is destroyed.

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

This function must be overloaded when creating a :doc:`/types/Script/index` and is executed once, when the :doc:`/types/Scriptable/index` Component attached to an :doc:`/types/Entity/index` is destroyed.