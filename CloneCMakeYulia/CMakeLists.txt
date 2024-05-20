cmake_minimum_required(VERSION 2.8)      

set(PROJECT_NAME Yulia)				 		 
project("${PROJECT_NAME}")


set(CMAKE_CXX_STANDART 14)			 


include_directories("inc/")

add_executable("${PROJECT_NAME}" Laba_2.cpp)
