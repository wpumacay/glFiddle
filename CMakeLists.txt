
cmake_minimum_required( VERSION 3.5.0 )
project( glFiddle C CXX )

message( "cmake source dir: ${CMAKE_SOURCE_DIR}" )
message( "cmake build dir: ${CMAKE_BINARY_DIR}" )


add_subdirectory( ext )
add_subdirectory( tests )
