Scripting Basics
================

**Scripts** are pieces of code that give a **behaviour** to **Entities**.

To create a new Script, create a new file with a ``.h`` file extension in the ``scripts`` directory at the root of the project directory.

In it, copy and paste this script template:

.. code-block:: cpp

	#pragma once
	#include "../Core/scripting/ntshengn_scripting_api.h"

	using namespace NtshEngn;
	struct TemplateScript : public ScriptingAPI {
		NTSHENGN_SCRIPT(TemplateScript);

		void init() {
		}

		void update(double dt) {
		}

		void destroy() {
		}
	};

``ScriptingAPI`` is a structure containing the :doc:`/scripting/api/index`, allowing to call functions from NutshellEngine's systems.

