# TF Note

Seems to be issues with publishing transforms for multiple cameras, even after following the suggested fix on the realsense repo (use dynamic transforms, https://github.com/intel-ros/realsense/issues/120)

As a work around, all camera frames are hard coded into the urdf file for the base platform. See https://github.com/max-mobility/iCreateRosUtils 