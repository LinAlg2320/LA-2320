LA-2320
=======

This is a repository for Linear Algebra 2320 presentation

Group Members: Justin, Dawson, other dude

Linear Algebra related concept: Vector based collision detection game.

Game concept: Very basic oldschool shooter game. Turret shoots meteors out of the sky that are falling towards the
turret.

Static turret in the bottom center of a NxN gameboard. The turret has the ability to move the angle
at which a projectile can be launched. Based on the direction chosen by the user, the fire button will fire a 
projectile with the chosen direction and given an initial velocity. The projectile will then continue on its path until
one of two things happen. If it hits the left or right side of the gameboard it bounces off and continues on a new
path with a reduced velocity. Each subsequent bounce will cause a reduction in velocity. The second option is the 
projectile hits a meteor where the projectile and the meteor are destroyed.

              