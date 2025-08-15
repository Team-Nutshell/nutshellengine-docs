isPlatformAchievementUnlocked
=============================

:doc:`/types/PlatformModuleInterface/index`::isPlatformAchievementUnlocked

Checks if an achievement has been unlocked.

Declaration
-----------

.. code-block:: cpp

	bool isPlatformAchievementUnlocked(const std::string& achievementID);

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