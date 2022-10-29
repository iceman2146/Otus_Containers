cmake_minimum_required(VERSION 3.1)
project(cmake-example)

add_executable(main 
main.cpp
"SequenceContainer.h"
"OneWayList.h"
"TwoWayList.h"
)


set_target_properties(main PROPERTIES CXX_STANDARD 17 CXX_STANDARD_REQUIRED ON)
