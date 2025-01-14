0.10.15 (2021-05-11)
--------------------
* Merge pull request `#47 <https://github.com/ros-perception/calibration/issues/47>`_ from PR2-prime/noetic-devel
  Noetic devel
* fixed test errors for python3 compatibility
* fixed python3 compatibility issues
* update maintainer for most packages; first try at setup for travis testing (`#46 <https://github.com/ros-perception/calibration/issues/46>`_)
* more python3 package fixes
* more python3 package fixes
* only depend on python_orocos_kdl for python2
* spell exec correctly
* updated package.xml file for python3 dependencies
* Contributors: Dave Feil-Seifer

0.10.14 (2016-04-16)
--------------------
* remove useless dependency
* fix bad PyKDL usage
  fixes `#39 <https://github.com/ros-perception/calibration/issues/39>`_
* get rid of the tf dependency
* Contributors: Vincent Rabaud

0.10.13 (2014-12-21)
--------------------
* Fill previous_pose_guesses by zero if no initial_poses file exists
* Fix to use stream rather than file name to load initial_poses yaml file
* check if frame_id from bagfile and system.yaml is same
* Contributors: Kei Okada, Ryohei Ueda

0.10.12 (2014-09-21)
--------------------
* disable covariance for now
* fix tests
* get checkerboard properly centerd and fix test
* Contributors: Vincent Rabaud

0.10.11 (2014-09-20)
--------------------
* add warning if robot_description is not present in bag file
* axis is already list
* -Add markers showing id of calibration targets
* Contributors: Kei Okada, Stefan Kohlbrecher

0.10.10 (2014-05-06)
--------------------
* Export architecture_independent flag in package.xml
* Contributors: Scott K Logan

0.10.9 (2014-04-09)
-------------------

0.10.8 (2014-03-07)
-------------------
* check for CATKIN_ENABLE_TESTING
* Contributors: Lukas Bulwahn

0.10.7 (2014-01-15)
-------------------
- fix more issues related to #21

0.10.6 (2013-12-08)
-------------------
- fix #21
