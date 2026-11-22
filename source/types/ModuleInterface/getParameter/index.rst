getParameter
============

:doc:`/types/ModuleInterface/index`::getParameter

Returns a :doc:`/module/index` parameter.

Declaration
-----------

.. code-block:: cpp

	virtual void* getParameter(const std::string& parameterName);

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
	  - The parameter's name to get the value from.

Returns
-------

A pointer to the parameter associated to ``parameterName``. The actual pointer type should be found on the :doc:`/module/index`'s documentation.

If no parameter is associated to ``parameterName``, this function returns ``nullptr``.