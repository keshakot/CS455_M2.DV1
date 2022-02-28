CS455 Module 1 PR5: Ballistics++  
Author: Georgiy Antonovich Bondar  

Go to https://keshakot.github.io/CS455_M1.PR5/ to play the game :)

# Behaviors
Projectile Firer: Assets/Scripts/ProjectileFirer.cs   
Improved Projectile Firer: Assets/Scripts/ProjectileFirer_Improved.cs  

# Changes
1. Created an improved projectile firer which adjusts for misses and allows moving targets to be hit.  
2. Projectiles fired by this improved firer will, when they hit their target point, report to the firer the distance by which they missed their target. The firer then adjusts the lead accordingly, eventually hitting the moving target.  

# Bugs/issues
1. If the target is accelerating it will never be hit, for the lead will always be increasing.
2. Target aquisition is slow and not as precise as would be desired - it takes several attempts to 'home in' on the target.   
 
