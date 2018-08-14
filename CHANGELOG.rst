5.3.0 (2018-8-14)
---------------------------------
- No new changes for this repository

5.2.0 Patch (2018-4-16)
---------------------------------
- Adds new URDF Xacro Args (removable pedestal, fixed pose in Gazebo)
- Removes minimum inertia macro, as gravity comp is properly calculated

5.2.0 (2018-3-14)
---------------------------------
- Adds Xacro framework for the electric gripper URDF
- Adds Xacro framework for Gazebo URDF tags
- Updates Sawyer meshes (stl's and dae's)
- Limits J6 URDF position limits in Gazebo, to [-pi, pi]
  due to limitation of gazebo_ros_control joint readings

5.1.0 (2017-3-27)
---------------------------------
- Moved to Apache 2.0 license
- Added Contribution Guidelines
- Updated URDF for more accurate masses and inertial values for links
- Tightens collision shapes in URDF

5.0.4 (2016-12-06)
---------------------------------
- Initial release of sawyer_robot and sawyer_description packages
- sawyer_robot is a metapackage for sawyer_description
- sawyer_description contains all URDF and meshes required to visualize the Sawyer robot                                                                         
