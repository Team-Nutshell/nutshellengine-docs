lateUpdate
==========

:doc:`/types/ScriptBase/index`::lateUpdate

Is executed each frame, after the potential `PhysicsModule <https://github.com/Team-Nutshell/NutshellEngine-PhysicsModule/tree/main>`_ update.

Declaration
-----------

.. code-block:: cpp

	virtual void lateUpdate(float dt);

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
	  - The **delta time**, which corresponds to the time between two frames, in **seconds**.

Returns
-------

None.

Notes
-----

This function can be overloaded when creating a :doc:`/types/Script/index` and is executed once per frame, after the potential `PhysicsModule <https://github.com/Team-Nutshell/NutshellEngine-PhysicsModule/tree/main>`_ update.

