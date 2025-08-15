lockAchievement
===============

:doc:`/types/PlatformModuleInterface/index`::lockAchievement

Locks an achievement.

Declaration
-----------

.. code-block:: cpp

	virtual void lockAchievement(const std::string& achievementID) = 0;

Parameters
----------

.. list-table::
	:width: 100%
	:header-rows: 1
	:class: code-table

	* - Name
	  - Type
	  - Description
	* - achievementID
	  - const `std::string <https://en.cppreference.com/w/cpp/string/basic_string>`_\&
	  - The achievement to lock.

Returns
-------

None.