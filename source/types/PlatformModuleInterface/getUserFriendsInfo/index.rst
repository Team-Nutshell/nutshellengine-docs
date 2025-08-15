getUserFriendsInfo
==================

:doc:`/types/PlatformModuleInterface/index`::getUserFriendsInfo

Returns the list of the user's friends on the platform.

Declaration
-----------

.. code-block:: cpp

	virtual std::vector<PlatformUserInfo> getUserFriendsInfo() = 0;

Parameters
----------

None.

Returns
-------

An `std::vector <https://en.cppreference.com/w/cpp/container/vector>`_ of :doc:`/types/PlatformUserInfo/index` containing information about the user's friends on the platform.