getKeys
=======

:doc:`/types/JSON/Node/index`::getKeys

Returns all keys of an Object Node.

Declaration
-----------

.. code-block:: cpp

	const std::vector<std::string> getKeys() const;

Parameters
----------

None.

Returns
-------

An `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_ containing all keys of an Object :doc:`/types/JSON/Node/index`.

Notes
-----

This function can only be called on a :doc:`/types/JSON/Node/index` with the Object :doc:`/types/JSON/Type/index`.