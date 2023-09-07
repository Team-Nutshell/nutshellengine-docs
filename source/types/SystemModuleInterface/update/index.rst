update
======

:doc:`/types/SystemModuleInterface/index`::update

Update function executed once per frame.

Declaration
-----------

.. code-block:: cpp

	virtual void update(double dt) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - dt
	  - double
	  - The **delta time**, which corresponds to the time between two frames, in **milliseconds**.

Returns
-------

None.

Notes
-----

This function must be overloaded when creating a :doc:`/types/SystemModuleInterface/index` and is executed once per frame.