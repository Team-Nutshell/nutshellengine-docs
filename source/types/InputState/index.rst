InputState
==========

Declaration
-----------

.. code-block:: cpp

	enum class InputState {
		None,
		Pressed,
		Held,
		Released
	};

Notes
-----

.. image:: /assets/input_state.png

Input state transitions. A transition happens **each frame**, which means:

- An input is ``Pressed`` one frame and will become ``Held`` next frame if it is not released.
- An input is ``Released`` one frame and will become ``None`` next frame if it is not pressed.