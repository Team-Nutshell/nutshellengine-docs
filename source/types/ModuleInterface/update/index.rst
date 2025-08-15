update
======

:doc:`/types/ModuleInterface/index`::update

Update function executed once per frame.

Declaration
-----------

.. code-block:: cpp

	virtual void update(float dt) = 0;

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
	  - float
	  - The **delta time**, which corresponds to the time between two frames, in **seconds**.

Returns
-------

None.

Notes
-----

This function must be overloaded when creating a :doc:`/types/ModuleInterface/index` and is executed once per frame.