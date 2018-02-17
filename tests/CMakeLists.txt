

find_package( OpenGL REQUIRED )

include_directories( "${CMAKE_BINARY_DIR}/ext/glad/include"
					 "${CMAKE_SOURCE_DIR}/ext/glfw/include" )

add_executable( test1
				test1.cpp )

target_link_libraries( test1
					   glfw glad
					   ${OPENGL_LIBRARIES} )