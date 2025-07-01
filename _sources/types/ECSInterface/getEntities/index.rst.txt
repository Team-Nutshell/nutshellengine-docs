getEntities
===========

:doc:`/types/ECSInterface/index`::getEntities

Returns all the :doc:`Entities </entity_component_system/entity/index>`.

Declaration
-----------

.. code-block:: cpp

	virtual const std::set<Entity>& getEntities() = 0;

Parameters
----------

None.

Returns
-------

An `std::set <https://en.cppreference.com/w/cpp/container/set>`_\<:doc:`/entity_component_system/entity/index`> containing all the :doc:`Entities </entity_component_system/entity/index>`.