LightType
=========

Declaration
-----------

.. code-block:: cpp

	enum class LightType {
		Directional,
		Point,
		Spot,
		Ambient,
		Unknown
	};

Notes
-----

LightType is an enum used in :doc:`/types/Light/index` to differentiate the different types of lights.

- ``Directional``: A directional light emits parallel light rays (in its direction) on the whole scene.

.. image:: /assets/directional_light.png

- ``Point``: A point light emits light rays from its position, all around it.

.. image:: /assets/point_light.png

- ``Spot`` : A spot light emits light rays from its position, to its direction in cones defined by its cutoff values.

.. image:: /assets/spot_light.png

- ``Ambient`` : An ambient light emits light on every surface.

.. image:: /assets/ambient_light.png
