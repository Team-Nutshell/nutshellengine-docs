System
======

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - entities
	  - `std::set <https://en.cppreference.com/w/cpp/container/set>`_\<:doc:`/types/Entity/index`>
	  - The system's entities.

Functions
---------

.. list-table::
	:width: 100%
	:widths: 30 70
	:header-rows: 1
	:class: code-table

	* - Name
	  - Description
	* - :doc:`/types/System/onEntityComponentAdded/index`
	  - Callback called when an :doc:`/types/Entity/index` receives a :doc:`/types/Component/index` tracked by this system.
	* - :doc:`/types/System/onEntityComponentRemoved/index`
	  - Callback called when an :doc:`/types/Entity/index` loses a :doc:`/types/Component/index` tracked by this system.

Notes
-----

``entities`` is the list of :doc:`Entities </types/Entity/index>` that have **at least** one of the :doc:`Components </types/Component/index>` tracked by this system.

.. toctree::
	:hidden:

	./onEntityComponentAdded/index.rst
	./onEntityComponentRemoved/index.rst