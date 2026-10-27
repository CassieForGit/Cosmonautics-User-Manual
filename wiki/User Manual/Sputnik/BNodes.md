## Basic Nodes

There are many nodes in the sputnik, however only some are mostly used.

The Solid Thruster Node is used to control a Solid Booster Thruster. It only has two inputs, those being Ignite and ID
Ignite is a boolean and when it's input is => 1 the Thruster with the corresponding ID is ignited.

The Thruster Node is used to control a Standard Thruster. It also has two inputs, those being Thrust and ID.
Thrust is a value between 0 (no Thr.) and 1000 (max Thr.) and is used to set the thrust of a Standard Thruster with the corresponding ID.

The Vectored Thruster Node is used to control a Vectored Thruster. It has four possible inputs, those being: ID, Thrust, Pitch and Yaw.
Pitch and Yaw are values which together set the direction of thrust of the Vector Thruster with the corresponding ID.

The RCS Node is identical to the Thruster Node expect for it being used instead for RCS jets.

The Functions node is used to make a custom node so to say. To make a proper function you first add a function node and then open it via double click with LMB or via the options tab accessed via RMB. To make an input add inside the function an "Input Node" and to make an output add an "Output" node. To exit the function press Esc.