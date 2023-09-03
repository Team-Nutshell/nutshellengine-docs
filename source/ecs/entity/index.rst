Entity
======

An **Entity** is the representation of an object, managed by the :doc:`/ecs/index` (ECS). It is defined as:

.. code-block:: cpp

	using Entity = uint32_t;

Creation
--------

Creating an Entity is done using the :doc:`/ecs/index`, either by calling the ECS's :doc:`ecs/functions/createEntity` functions or the :doc:`/scripting/api/index`'s :doc:`/scripting/api/ecs/createEntity/index` function.

These functions return an ``Entity`` which can then be used when referencing an Entity.

When created, an Entity already has a :doc:`/ecs/component/transform/index` Component.

Destruction
-----------

Destroying an Entity is done using the :doc:`/ecs/index`, either by calling the ECS's :doc:`ecs/functions/destroyEntity` function or the :doc:`/scripting/api/index`'s :doc:`/scripting/api/ecs/destroyEntity/index` function.

Name
----

An Entity can have a name, which allows to find it using :doc:`ecs/functions/findEntityByName`.

Persistence
-----------

An Entity can be persistent.

When the scene changes, all **non-persistent** Entities are destroyed, while all **persistent** Entities stay. This can be used to pass data between scenes.