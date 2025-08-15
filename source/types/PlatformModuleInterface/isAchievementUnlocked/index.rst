isAchievementUnlocked
=====================

:doc:`/types/PlatformModuleInterface/index`::isAchievementUnlocked

Checks if an achievement has been unlocked.

Declaration
-----------

.. code-block:: cpp

	virtual bool isAchievementUnlocked(const std::string& achievementID) = 0;

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
	  - The achievement to check the unlock state.

Returns
-------

``true`` if the achievement has been unlocked by the user, else, returns ``false``.