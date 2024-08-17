setConstantForces
=================

:doc:`/types/PhysicsModuleInterface/index`::setConstantForces

Sets the constant forces.

Declaration
-----------

.. code-block:: cpp

	virtual void setConstantForces(const Math::vec3& constantForces) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - constantForces
	  - const :doc:`/types/Math/index`::vec3&
	  - The new constant forces.

Returns
-------

None.