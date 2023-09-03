Scriptable
==========

Declaration
-----------

.. code-block:: cpp

	struct Scriptable {
		Scriptable() = default;
		~Scriptable() = default;
		Scriptable(const Scriptable& other);
		Scriptable(Scriptable&& other) = default;
		Scriptable& operator=(const Scriptable& other);
		Scriptable& operator=(Scriptable&& other) = default;

		std::unique_ptr<Script> script = nullptr;
	};

Variables
---------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - script
	  - `std::unique_ptr <https://en.cppreference.com/w/cpp/memory/unique_ptr>`_\<Script>
	  - The script to use.
