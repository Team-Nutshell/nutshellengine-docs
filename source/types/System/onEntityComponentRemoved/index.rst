onEntityComponentRemoved
========================

:doc:`/types/System/index`::onEntityComponentRemoved

Callback called when an :doc:`/types/Entity/index` loses a :doc:`/types/Component/index` tracked by this system.

Declaration
-----------

.. code-block:: cpp

	virtual void onEntityComponentRemoved(Entity entity, Component componentID);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - entity
	  - :doc:`/types/Entity/index`
	  - The :doc:`/types/Entity/index` that lost the :doc:`/types/Component/index`.
	* - componentID
	  - :doc:`/types/Component/index`
	  - The lost :doc:`/types/Component/index`'s identifier.

Returns
-------

None.

Notes
-----

This function is meant to be overloaded by the :doc:`/types/System/index` and is called when an :doc:`/types/Entity/index` loses a :doc:`/types/Component/index` tracked by this system.