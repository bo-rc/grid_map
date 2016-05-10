^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package grid_map_cv
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------

1.3.0 (2016-04-26)
------------------
* Separated OpenCV to grid map conversions to grid_map_cv package. The new methods
  are more generalized, faster, and can be used without ROS message types.
* Added new convenience function to change the resolution of grid maps with help of the OpenCV interpolation methods.
* Added `initializeFromImage()` to GridMapCvConverter.
* Added unit tests for grid_map_cv. Updated documentation.
* Resolving build errors for OpenCV.
* Fixed typo and added documentation.
* Contributors: Peter Fankhauser, Dominic Jud,