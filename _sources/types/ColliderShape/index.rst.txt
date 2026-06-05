ColliderShape
=============

Declaration
-----------

.. code-block:: cpp

	typedef std::variant<ColliderBox, ColliderSphere, ColliderCapsule> ColliderShape;

Notes
-----

Being a `std::variant <https://en.cppreference.com/cpp/utility/variant>`_, it is possible to check if it contains a :doc:`/types/ColliderBox/index`, :doc:`/types/ColliderSphere/index` or a :doc:`/types/ColliderCapsule/index` by using `std::holds_alternative <https://en.cppreference.com/cpp/utility/variant/holds_alternative>`_ (for example: ``std::holds_alternative<ColliderBox>(collider)`` will return ``true`` if the ColliderShape contains a ColliderBox) and get the real collider with `std::get <https://en.cppreference.com/cpp/utility/tuple/get>`_ (for example: ``ColliderBox& box = std::get<ColliderBox>(collider)``).