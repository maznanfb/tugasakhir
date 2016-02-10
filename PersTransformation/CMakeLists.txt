cmake_minimum_required(VERSION 2.8)
project( epipolar )
find_package( OpenCV REQUIRED )
add_executable( epipolar epipolar.cpp )
target_link_libraries( epipolar ${OpenCV_LIBS} )

