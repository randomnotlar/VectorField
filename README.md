# alpersunter.github.io/VectorField/

My original intention was to create animations about curl and divergence. Then I found myself playing with force fields.

  - PointParticle.js: Defines a simple point particle.
    - Mass
    - Radius
    - Electrical charge
    - Time speed

  - VectorField.js: For a given vector function V, draws samples of V in some part of the space.
    - Vector function
    - X, Y, Z limits
    - Arrow length
    - Arrow density

  - SpaceCodes.js: Useful codes for drawing in space.
    - PointYTo(vec) rotates XYZ axes so that new Y axis is now pointing along vector vec (which coordinates are with respect to space prior to rotations).
    - arrow3D(vec) draws an arrow for a given vector.
    - axes(planesVisible) draws X, Y and Z axes with the option to show XY YZ XZ planes (axes(true) or axes(false))
   
