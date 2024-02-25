to_string
=========

:doc:`/types/JSON/index`::to_string

Converts the JSON to a string.

Declaration
-----------

.. code-block:: cpp

	static std::string to_string(const Node& node);

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - node
	  - const :doc:`/types/JSON/Node/index`\&
	  - The root :doc:`/types/JSON/Node/index`.

Returns
-------

The JSON string for the whole hierarchy, with ``node`` as root.