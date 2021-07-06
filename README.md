# robot_2dnav

Set up a map (includes yaml and pgm file) using SLAM mapping.
Change the map file location in move_base.launch accordingly.
There are 3 planners to choose from, the default planner will be teb_local_planner.

If the robot changes:
- Change the incribed and circumscribed radius under costmap_common_params.

Current resolution is 0.03.
