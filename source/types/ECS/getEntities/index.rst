getEntities
===========

:doc:`/types/ECS/index`::getEntities

Returns all the :doc:`Entities </entity_component_system/entity/index>`.

Declaration
-----------

.. code-block:: cpp

	const std::set<Entity>& getEntities();

Parameters
----------

None.

Returns
-------

An `std::set <https://en.cppreference.com/w/cpp/container/set>`_\<:doc:`/entity_component_system/entity/index`> containing all the :doc:`Entities </entity_component_system/entity/index>`.