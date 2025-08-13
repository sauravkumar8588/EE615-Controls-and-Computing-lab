Open Exp2.m
Run the Exp2.m

It opens an simulink file name pathFollowingwithObstacleAvoidanceExample

There will be two blocks one for Purepursuit Algorithm(Compute Velocity and Heading for Path following), One for VFH(Adjust Velocities to Avoid Obstacles).If each of the block is clicked in it,it's mentioned where the algorithm has to be implemented. Existing blocks are inbuilt blocks, it has to replaced with your own Matlab functions.

Also in simulink file there is an Inputs block, after clicking Inputs block there is an option to select Waypoints Input.

Run the simulink file to see the bot moving.

Idea is to reach the destination by following the waypoints and avoiding the obstacles.

Make sure to use rosshutdown everytime before running the slx file