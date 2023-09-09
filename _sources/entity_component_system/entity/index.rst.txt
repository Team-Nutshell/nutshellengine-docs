Entity
======

An **Entity** is the representation of an object, managed by the :doc:`/entity_component_system/index` (ECS). It is defined as:

Creation
--------

Creating an Entity is done using the :doc:`/entity_component_system/index`, either by calling the ECS' :doc:`/types/ECS/createEntity/index` functions or the :doc:`/scripting/api/index`'s :doc:`/types/Script/createEntity/index` function.

These functions return an ``Entity`` which can then be used when referencing an Entity.

When created, an Entity already has a :doc:`/types/Transform/index` Component.

Destruction
-----------

Destroying an Entity is done using the :doc:`/entity_component_system/index`, either by calling the ECS's :doc:`/types/ECS/destroyEntity/index` function or the :doc:`/scripting/api/index`'s :doc:`/types/Script/destroyEntity/index` function.

Name
----

An Entity can have a name, which allows to find it using the ECS' :doc:`/types/ECS/findEntityByName/index` or the :doc:`/scripting/api/index`'s :doc:`/types/Script/findEntityByName/index` function.

Persistence
-----------

An Entity can be persistent.

When the scene changes, all **non-persistent** Entities are destroyed, while all **persistent** Entities stay. This can be used to pass data between scenes.