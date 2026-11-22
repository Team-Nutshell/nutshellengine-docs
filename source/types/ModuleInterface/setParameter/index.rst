setParameter
============

:doc:`/types/ModuleInterface/index`::setParameter

Sets a :doc:`/module/index` parameter value.

Declaration
-----------

.. code-block:: cpp

	virtual void setParameter(const std::string& parameterName, void* data);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - parameterName
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The parameter's name to set the value of.
	* - data
	  - void*
	  - A pointer to the data.

Returns
-------

None.

Notes
-----

If there is no parameter associated to ``parameterName``, this function has no effect.

The actual type of ``data`` should be found on the :doc:`/module/index`'s documentation.