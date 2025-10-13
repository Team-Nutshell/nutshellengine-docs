setMasterGain
=============

:doc:`/types/AudioModuleInterface/index`::setMasterGain

Sets the master gain.

Declaration
-----------

.. code-block:: cpp

	virtual void setMasterGain(float newGain) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - newGain
	  - float
	  - The new master gain.

Returns
-------

None.

Notes
-----

The master gain is the overall volume of all sounds.