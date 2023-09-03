Scripting Basics
================

**Scripts** are pieces of code that give a **behaviour** to **Entities**.

To create a new Script, create a new file with a ``.h`` file extension in the ``scripts`` directory at the root of the project directory.

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

``Script`` is a structure containing the :doc:`/scripting/api/index`, allowing to call functions from NutshellEngine's systems.

