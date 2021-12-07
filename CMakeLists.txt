## This CMakeLists.txt file exists only for building as ROS 3rd-party package. Building for other purpose is not tested. See https://github.com/AndreaCensi/csm/pull/10
cmake_minimum_required (VERSION 2.8)#cmake最低版本为2.8

project (csm)#工程名为csm

add_subdirectory (src)#将lib_func这个文件夹设为子目录
