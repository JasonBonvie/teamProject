cmake_minimum_required (VERSION 2.6)
project (Rubix)

set (CMAKE_CXX_STANDARD 11)
add_compile_options(-std=c++11)

add_executable(Rubix
	rubix.cpp
	ShiftArray.cpp
	ShiftArray.hpp
	RCube.cpp
	RCube.hpp
	RCubeSolver.cpp
	RCubeSolver.hpp
	INode.hpp
	Input.cpp
	Input.hpp
	Output.cpp
	Output.hpp
)
