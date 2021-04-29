# Submission checklist and requirements
Once your team's project is able to drive the vehicle successfully in the simulator, you may be ready to submit the project for testing on the Udacity vehicle. At this point, your project should:

1. Launch correctly using the launch files provided in the capstone repo. Please note that we will not be able to accommodate special launch instructions or run additional scripts from your submission to download files. The launch/styx.launch and launch/site.launch files will be used to test code in the simulator and on the vehicle respectively. The submission size limit for this project has been increased to 2GB.
2. Smoothly follow waypoints in the simulator.
3. Respect the target top speed set for the waypoints' twist.twist.linear.x in waypoint_loader.py. Be sure to check that this is working by testing with different values for kph velocity parameter in /ros/src/waypoint_loader/launch/waypoint_loader.launch. If your vehicle adheres to the kph target top speed set here, then you have satisfied this requirement.
4. Stop at traffic lights when needed.
5. Stop and restart PID controllers depending on the state of /vehicle/dbw_enabled.
6. Publish throttle, steering, and brake commands at 50hz.


# Account Names
...
