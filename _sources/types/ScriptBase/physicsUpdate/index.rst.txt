physicsUpdate
=============

:doc:`/types/ScriptBase/index`::physicsUpdate

Is executed each time the :doc:`/module/physics_module/index` does a physics iteration.

Declaration
-----------

.. code-block:: cpp

	virtual void physicsUpdate(float dt) {

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - dt
	  - float
	  - Delta time of the physics iteration, in **seconds**.

Returns
-------

None.

Notes
-----

As this function is executed **per physics iteration and not per frame**, it means that **it can be executed 0, 1 or N times per frame**.