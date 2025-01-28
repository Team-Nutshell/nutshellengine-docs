Starting with NutshellEngine
============================

As a game developer
-------------------

As a game developer, you must start by `downloading NutshellEngine from itch.io <https://team-nutshell.itch.io/nutshellengine>`_. This will give you access to the **editor**, the **engine's core** and a set of **already made modules**.

The **editor** is the interface you can use to create your game, it allows you to easily create your scenes, define your entities and give them components.

The **engine's core** is the **executable** file. It is the **same** for all games made with NutshellEngine and is the central piece to the modularity of NutshellEngine. Its role is to load all modules, including the script module that will be created when you want to build and run your game.

The **modules** are the different systems of NutshellEngine, like window system and inputs, graphics, physics and audio. NutshellEngine is a **modular game engine**, so all these systems aren't part of the **executable**, instead, they are **dynamic libraries** files that you can swap to change how your game runs, sounds or looks, **without recompiling the engine or your game**. NutshellEngine comes with a set of selected modules, for all types of modules.

When starting NutshellEngine for the first time and creating a new project, you might want to go into ``Options > Open Editor Parameters`` in the menu bar to change some parameters, like the inputs (by default, the keys assume you are using a *QWERTY* keyboard, which may not be adapted to your keyboard) or the code editor you use, which is used when opening and editing scripts.

If you don't use Windows or Linux
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

NutshellEngine is supported, tested and provided on both Windows and Linux, with an x64 architecture. If you don't use this configuration, you can try to compile each part of NutshellEngine's yourself, or add an issue in `NutshellEngine's main repository <https://github.com/Team-Nutshell/NutshellEngine>`_ so the support for the system you use can be studied and potentially added.

As an engine developer
----------------------

Contribute to NutshellEngine
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you want to contribute to NutshellEngine, you can open issues and pull requests in the adapted repository. For example, if you experience an issue or have an idea for NutshellEngine's core or in general, please refer to the `main repository <https://github.com/Team-Nutshell/NutshellEngine>`_, if it concerns graphics, please refer to the `GraphicsModule repository <https://github.com/Team-Nutshell/NutshellEngine-GraphicsModule>`_, if it's related to the editor, please refer to the `Editor repository <https://github.com/Team-Nutshell/NutshellEngine-Editor>`_, etc.

Developing your own modules
~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you want to develop your own modules, please refer to each module's repository (`GraphicsModule <https://github.com/Team-Nutshell/NutshellEngine-GraphicsModule/tree/main>`_, `PhysicsModule <https://github.com/Team-Nutshell/NutshellEngine-PhysicsModule/tree/main>`_, `WindowModule <https://github.com/Team-Nutshell/NutshellEngine-Windowodule/tree/main>`_, `AudioModule <https://github.com/Team-Nutshell/NutshellEngine-AudioModule/tree/main>`_, `AssetLoaderModule <https://github.com/Team-Nutshell/NutshellEngine-AssetLoaderModule/tree/main>`_).

The ``main`` branch of each repository contains the **empty base** for each module, where you can start from, but **you can also use any other branch as a base to expand from**.

A module follows an **interface**, you can find each interface in this documentation (:doc:`/types/GraphicsModuleInterface/index`, :doc:`/types/PhysicsModuleInterface/index`, :doc:`/types/WindowModuleInterface/index`, :doc:`/types/AudioModuleInterface/index`, :doc:`/types/AssetLoaderModuleInterface/index`). You don't have to implement all functions, if the function is not implemented, you can add the ``NTSHENGN_MODULE_FUNCTION_NOT_IMPLEMENTED()`` macro in the function, which will display a message in the console when the function gets called.

To **debug your module** (place breakpoints, read values, etc.), you will need to build NutshellEngine's core, available in the `main repository <https://github.com/Team-Nutshell/NutshellEngine>`_, put your module inside a ``modules`` directory next to NutshellEngine's executable, and refer to your IDE or compiler's instructions on how to debug dynamic libraries. You can add ``-DNTSHENGN_INSTALL_MODULE_PATH=<path/to/nutshellengine/modules>`` when **running the CMake** to install your modules directly in the ``modules`` directory next to NutshellEngine's executable.

.. toctree::
	:maxdepth: 1

