## Categories of Nodes

There are 14 Built-in categories.

The first one, the Actuators category, contains 4 nodes of which are used to control their respective block. A Thruster, a Vectored Thruster, a Booster (Solid Thruster) and RCS.
They all are independent between each other.

There is no use of the Audio category, use [CC:T speakers](https://tweaked.cc/peripheral/speaker.html)

In the Communication category you can use both the Create Redstone Link Network to Send and receive redstone signals, and also the Cosmonautics Sputlink Radio Network to send and receive values.

In the Conversion category you have 4 nodes which can convert integers, string and numbers to each other.

In the Deep Space category you can get information about your spacecraft like orbit info and velocity. Note that they work only in Deep Space.

With the Display category nodes you can view your number outputs and vectors. To view a string value please see *Strings*

The Functions category is a special one: to make a custom node you first make a function node and then open it via double click or via the options tab via RMB. To make an input for a custom node you add inside the function an "Input Node" and to make an input you add an "Output" node. To exit the function press Esc.

The Logic category contains nodes that use booleans and/or output them. 0 means false while 1 means true.

The Math category contains mathematical functions such as sin, but also basic ones like plus and minus but also vector functions like vector add.

The Programming category contains a Lua script node. It is like a function. Usage of CC:Tweaked Sputnik Peripheral is preferred. If not, please check out [Lua Script](/wiki/User%20Manual/Sputnik/LuaScripts.md).

The Sensors category contains all values that one might need when not in DeepSpace. The nodes output their corresponding value of the spacecraft. (eg. Altitude)

The String category has nodes which are used to work with strings, such as viewing a single character of a string, Displaying a string or adding two string together.

The System category contains the frame node. It is basically a way of commenting on the Sputnik. Usage is unnecessary and nesting with functions is preferred.
