project( Sobel )

cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
find_package( OpenCV REQUIRED)
include_directories( ${OpenCV_INCLUDE_DIRS} )
add_executable( Sobel main.cpp )
target_link_libraries( Sobel ${OpenCV_LIBS} )
