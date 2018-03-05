cmake_minimum_required(VERSION 3.5)
project(toyBDD CXX)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
        toyBDD.cpp
	main.cpp
    )

  add_executable(toyBDD ${SOURCE_FILES})

