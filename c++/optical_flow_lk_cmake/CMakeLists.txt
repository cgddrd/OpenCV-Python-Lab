cmake_minimum_required(VERSION 2.8)
project( lkdemo2 )
find_package( OpenCV )
include_directories( ${OpenCV_INCLUDE_DIRS} )
add_executable( lkdemo2 lkdemo.cpp )
target_link_libraries( lkdemo2 ${OpenCV_LIBS} )
