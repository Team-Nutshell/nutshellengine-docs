Scripting Basics
================

:doc:`Scripts </types/Script/index>` are pieces of code that give a **behaviour** to :doc:`Entities </entity_component_system/entity/index>`.

To create a new :doc:`/types/Script/index`, create a new file with a ``.h`` file extension in the ``scripts`` directory at the root of the project directory.

In it, copy and paste this script template:

.. code-block:: cpp

	#pragma once
	#include "../Core/scripting/ntshengn_script.h"

	using namespace NtshEngn;
	struct TemplateScript : public Script {
		NTSHENGN_SCRIPT(TemplateScript);

		void init() {
		}

		void update(double dt) {
		}

		void destroy() {
		}
	};

:doc:`/types/Script/index` is a structure containing the :doc:`/scripting/api/index`, allowing to call functions from NutshellEngine's systems.

:doc:`/types/Script/init/index` is a function that will be executed once, when the Script is created.

:doc:`/types/Script/update/index` is a function that will be executed once per frame. The ``dt`` parameter corresponds to the **delta time**, or the time between two frames, in **milliseconds**.

:doc:`/types/Script/destroy/index` is a function that will be executed once, when the Script is destroyed.