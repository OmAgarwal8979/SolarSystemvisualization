# SolarSystemvisualization
# INTRODUCTION
One of the uses of programming is to help us understand the real world through simulation. This
technique is used in science, finance, and many other quantitative fields. As long as the “rules”
which govern the real-world properties are known, you can write a computer program that
explores the outcomes you get from following those rules. In this , we’ll simulate a 3D solar
system in Python using the popular visualization library Matplotlib. <br />
## Concept of Gravity <br />
Suns, planets, and other objects in a solar system are bodies that are in motion and that attract
each other due to the gravitational force exerted between any two objects. If the two objects have
masses m1 and m 2 and are a distance of rr away, then you can calculate the gravitational force
between them using the following equation:<br />
** F=(G.m1.m2)/r^2
The constant G is a gravitational constant. You’ll see how you’ll be able to ignore this constant in
the version of the simulation you’ll write in this article in which you’ll use arbitrary units for
mass and distance rather than kg and m. <br />
Once you know the gravitational force between two objects, you can work out the acceleration aa
each object undergoes due to this gravitational force using the following formula:<br />
** F=ma
Using this acceleration, you can adjust the velocity of the moving object. When the velocity
changes, both the speed and the direction of travel will change.<br />
## Representing Points and Vectors in 3D
When simulating a 3D solar system in Python, we’ll need to represent the solar system as a region
of space using three dimensions. Therefore, each point in this 3D space can be represented using
three numbers, the x-, y-, and z-coordinates. For example, if you wish to place a sun in the center
of the solar system, you can represent the sun’s position as (0, 0, 0). You’ll also need to represent
vectors in 3D space. A vector has both magnitude and direction. You’ll need vectors for quantities
such as velocity, acceleration, and force since these quantities all have a direction as well as a
magnitude.<br />
# OBJECTIVE
1. A brief discussion about the gravitational attraction between two bodies which you’ll need
to use for simulating a 3D solar system in Python.
2. Definition of classes for the solar system and the orbiting bodies within it, such as suns and
planets.
3. Addition of the option to show a 2D projection of the orbiting bodies along with the 3D
simulation. This 2D projection helps to visualize the motion in 3D.
4. Creation of a binary star system.
