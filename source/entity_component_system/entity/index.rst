Entity
======

An **Entity** is the representation of an object, managed by the :doc:`/entity_component_system/index` (ECS). It is defined as:

.. code-block:: cpp

	using Entity = uint32_t;

Creation
--------

Creating an Entity is done using the :doc:`/entity_component_system/index`, either by calling the ECS' :doc:`/entity_component_system/ecs/createEntity/index` functions or the :doc:`/scripting/api/index`'s :doc:`/scripting/script/createEntity/index` function.

These functions return an ``Entity`` which can then be used when referencing an Entity.

When created, an Entity already has a :doc:`/entity_component_system/component/Transform/index` Component.

Destruction
-----------

Destroying an Entity is done using the :doc:`/entity_component_system/index`, either by calling the ECS's :doc:`/entity_component_system/ecs/destroyEntity/index` function or the :doc:`/scripting/api/index`'s :doc:`/scripting/script/destroyEntity/index` function.

Name
----

An Entity can have a name, which allows to find it using the ECS' :doc:`/entity_component_system/ecs/findEntityByName/index` or the :doc:`/scripting/api/index`'s :doc:`/scripting/script/findEntityByName/index` function.

Persistence
-----------

An Entity can be persistent.

When the scene changes, all **non-persistent** Entities are destroyed, while all **persistent** Entities stay. This can be used to pass data between scenes.