getComponentMask
================

:doc:`/types/SystemModuleInterface/index`::getComponentMask

Returns the tracked :doc:`Components </types/Component/index>`.

Declaration
-----------

.. code-block:: cpp

	virtual const ComponentMask getComponentMask() const;

Parameters
----------

None.

Returns
-------

A bitmask of the :doc:`/types/SystemModuleInterface/index`'s tracked :doc:`Components </types/Component/index>`.

Notes
-----

This function is meant to be overloaded when creating a :doc:`/types/SystemModuleInterface/index`.