emitParticles
=============

:doc:`/types/GraphicsModuleInterface/index`::emitParticles

Emits particles described by a :doc:`/types/ParticleEmitter/index`.

Declaration
-----------

.. code-block:: cpp

	virtual void emitParticles(const ParticleEmitter& particleEmitter) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - particleEmitter
	  - :doc:`/types/ParticleEmitter/index`
	  - The :doc:`/types/ParticleEmitter/index` describing the particles to emit.

Returns
-------

None.